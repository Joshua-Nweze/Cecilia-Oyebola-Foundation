<template>
    <div>
        <NuxtLayout>
          <!-- custom mouse effect -->
            <div
                class="fixed top-0 left-0 w-4 h-4 bg-yellow-400 rounded-full pointer-events-none z-[9999]"
                :style="{
                    transform: `translate3d(${dotX}px, ${dotY}px, 0)`,
                    transition: 'transform 0.1s ease-out',
                }"
            ></div>

            <Nav />
            <div class="mt-20">
                <NuxtPage />
            </div>
            <SharedPurpose />
            <Footer />
        </NuxtLayout>
    </div>
</template>

<script setup>
const mouseX = ref(0);
const mouseY = ref(0);
const dotX = ref(0);
const dotY = ref(0);

let animationFrameId;

const updatePosition = () => {
    dotX.value += (mouseX.value - dotX.value) * 0.15;
    dotY.value += (mouseY.value - dotY.value) * 0.15;
    animationFrameId = requestAnimationFrame(updatePosition);
};

const handleMouseMove = (e) => {
    mouseX.value = e.clientX;
    mouseY.value = e.clientY;
};

onMounted(() => {
    window.addEventListener("mousemove", handleMouseMove);
    animationFrameId = requestAnimationFrame(updatePosition);
});

onUnmounted(() => {
    window.removeEventListener("mousemove", handleMouseMove);
    cancelAnimationFrame(animationFrameId);
});
</script>
