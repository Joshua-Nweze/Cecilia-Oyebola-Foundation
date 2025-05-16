<template>
    <div class="grid gap-20">
        <!-- hero -->
        <div class="overflow-hidden bg-white py-16">
            <div class="mx-auto max-w-7xl">
                <div class="mx-auto grid max-w-2xl grid-cols-1 gap-x-8 gap-y-16 sm:gap-y-20 lg:mx-0 lg:max-w-none lg:grid-cols-2">
                    <div class="lg:pt-4 lg:pr-8">
                        <div class="h-full flex flex-col justify-center lg:max-w-lg">
                        <h2 class="mt-2 text-5xl font-semibold tracking-tight text-pretty text-gray-900">Empowering lives</h2>
                        <h2 class="mt-2 text-5xl font-semibold tracking-tight text-pretty text-gray-900">Empowering communities</h2>
                        <p class="mt-6 text-lg/8 text-gray-600">Access to education, healthcare, and self-development should be a right, not a privilege, for every individual, no matter who or where they are.</p>
                        <div class="mt-8">
                            <PrimaryBtn>Get started</PrimaryBtn>
                        </div>
                        </div>
                    </div>
                    <img src="https://tailwindcss.com/plus-assets/img/component-images/dark-project-app-screenshot.png" alt="Product screenshot" class="w-[48rem] max-w-none rounded-xl shadow-xl ring-1 ring-gray-400/10 sm:w-[57rem] md:-ml-4 lg:-ml-0" width="2432" height="1442">
                </div>
            </div>
        </div>

        <div class="lg:px-30 grid gap-20">
            <div class="grid lg:grid-cols-2 gap-5">
                <div class="relative">
                    <img class="w-[80%] shadow-xl absolute top-10" src="https://images.unsplash.com/photo-1726549384638-e530b978ac3e?q=80&w=2069&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="">
                    <img class="w-1/2 shadow-xl absolute top-1 right-1" src="https://images.unsplash.com/photo-1735615479490-237b941e996a?q=80&w=1932&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="">
                    <img class="w-1/2 shadow-xl absolute top-60 right-1" src="https://images.unsplash.com/photo-1734623044490-4bf667aafade?q=80&w=2063&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="">
                </div>
                <div>
                    <h3 class="mt-2 text-3xl font-semibold tracking-tight text-pretty text-gray-900">Who we are</h3>
    
                    <p class="mt-6 text-lg/8 text-gray-600">At the Cecilia Oyebola Foundation, we are driven by a singular mission: to create opportunities that transform lives. Founded with a vision to empower underserved communities, we focus on providing children, including both boys and girls, as well as women and the elderly in resource-insecure areas, access to quality education, essential healthcare, and personal development resources.​
    
                    We aim to bridge the gap between people and their dreams, breaking the cycle of poverty and building a brighter future for all.​
    
                    The Cecilia Oyebola Foundation is more than an organization; it is a movement dedicated to fostering growth, equity, and dignity in every life we touch.</p>
                    <div class="mt-8">
                        <PrimaryBtn>Who we are</PrimaryBtn>
                    </div>
                </div>
            </div>
    
            <div class="grid lg:grid-cols-2 gap-5">
                <div>
                    <h3 class="mt-2 text-3xl font-semibold tracking-tight text-pretty text-gray-900">What we do</h3>
                    <p class="mt-6 text-lg/8 text-gray-600">At the Cecilia Oyebola Foundation, we create programs that address critical needs where they matter most.
    
                    Our focus spans education, healthcare, and personal development, reaching those with limited resources.
                    We aim to provide opportunities that empower individuals to unlock their full potential.
                    Every initiative is designed to foster lasting change and drive meaningful impact.
                    Through these efforts, we are helping build brighter, more hopeful futures.</p>
                </div>
                <div>
            
                </div>
            </div>
    
        </div>
        
        <TestimonyCarousel />

    </div>
</template>

<style scoped>
img {
    box-shadow: 10px;
}
</style>