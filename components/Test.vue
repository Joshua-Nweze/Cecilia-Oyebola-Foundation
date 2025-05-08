<!-- components/TestimonyCarousel.vue -->
<template>
    <div class="relative overflow-hidden w-full max-w-2xl mx-auto">
      <div
        class="flex transition-transform duration-500 ease-in-out"
        :style="{ transform: `translateX(-${currentSlide * 100}%)` }"
      >
        <div
          v-for="(testimony, index) in testimonies"
          :key="index"
          class="w-full flex-shrink-0 p-6 text-center bg-white rounded-lg shadow"
        >
          <p class="text-gray-700 italic">"{{ testimony.message }}"</p>
          <h4 class="mt-4 font-semibold text-[#E36D01]">{{ testimony.name }}</h4>
          <span class="text-sm text-gray-500">{{ testimony.title }}</span>
        </div>
      </div>
  
      <!-- Controls -->
      <div class="absolute top-1/2 -translate-y-1/2 w-full flex justify-between px-4">
        <button
          @click="prev"
          class="bg-gray-800/50 hover:bg-gray-800 text-white p-2 rounded-full"
        >
          ‹
        </button>
        <button
          @click="next"
          class="bg-gray-800/50 hover:bg-gray-800 text-white p-2 rounded-full"
        >
          ›
        </button>
      </div>
  
      <!-- Dots -->
      <div class="flex justify-center mt-4 gap-2">
        <button
          v-for="(_, i) in testimonies"
          :key="i"
          class="w-3 h-3 rounded-full"
          :class="{
            'bg-[#E36D01]': i === currentSlide,
            'bg-gray-300': i !== currentSlide
          }"
          @click="goToSlide(i)"
        ></button>
      </div>
    </div>
  </template>
  
  <script setup lang="ts">
  import { ref, onMounted, onUnmounted } from 'vue';
  
  const testimonies = [
    {
      name: 'Jane Doe',
      title: 'Client',
      message: 'This company has exceeded my expectations!',
    },
    {
      name: 'John Smith',
      title: 'Customer',
      message: 'Excellent service and timely delivery.',
    },
    {
      name: 'Mary Johnson',
      title: 'Partner',
      message: 'We’ve had a great experience working together.',
    },
  ];
  
  const currentSlide = ref(0);
  let intervalId: number;
  
  const next = () => {
    currentSlide.value = (currentSlide.value + 1) % testimonies.length;
  };
  
  const prev = () => {
    currentSlide.value =
      (currentSlide.value - 1 + testimonies.length) % testimonies.length;
  };
  
  const goToSlide = (index: number) => {
    currentSlide.value = index;
  };
  
  onMounted(() => {
    intervalId = setInterval(next, 10000); // auto-slide every 10 seconds
  });
  
  onUnmounted(() => {
    clearInterval(intervalId);
  });
  </script>
  