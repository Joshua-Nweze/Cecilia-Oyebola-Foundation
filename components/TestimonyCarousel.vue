<template>
    <div class="relative overflow-hidden w-full max-w-3xl mx-auto">
      <div
        class="flex transition-transform duration-500 ease-in-out"
        :style="{ transform: `translateX(-${currentSlide * 100}%)` }"
      >
        <div
          v-for="(testimony, index) in testimonies"
          :key="index"
          class="w-full flex-shrink-0 p-6 px-12 text-center bg-white rounded-lg shadow"
        >
          <p class="text-gray-700 italic">"{{ testimony.message }}"</p>
          <!-- <h4 class="mt-4 font-semibold text-[#E36D01]">{{ testimony.name }}</h4>
          <span class="text-sm text-gray-500">{{ testimony.title }}</span> -->
        </div>
      </div>
  
      <!-- Controls -->
      <div class="absolute top-1/2 -translate-y-1/2 w-full flex justify-between ">
        <button
          @click="prev"
          class="bg-gray-800/50 hover:bg-gray-800 text-white p-2 rounded-full h-10 w-10 cursor-pointer"
        >
          ‹
        </button>
        <button
          @click="next"
          class="bg-gray-800/50 hover:bg-gray-800 text-white p-2 rounded-full h-10 w-10 cursor-pointer"
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
            'bg-blue-500': i === currentSlide,
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
      message: ' We are committed to ensuring that every child has access to quality education, regardless of their financial background. Through our scholarship initiatives, we provide opportunities for students who cannot afford schooling, enabling them to pursue their academic goals. Additionally, we distribute educative materials such as books, stationery, and digital learning tools to equip learners with the resources they need to succeed. Our mentorship programs further support students by guiding them toward academic excellence and career achievements, fostering a generation of empowered and knowledgeable individuals.!',
    },
    {
      name: 'John Smith',
      title: 'Customer',
      message: 'Healthcare is a fundamental right, and we strive to make it accessible to communities in need. The foundation organizes regular outreaches to provide free healthcare services and raise awareness about critical health issues. We supply essential medical provisions and educate communities on hygiene, nutrition, and preventative healthcare practices. By addressing these basic health needs, we aim to build stronger and healthier communities capable of thriving.',
    },
    {
      name: 'Mary Johnson',
      title: 'Partner',
      message: 'Empowering individuals to achieve their dreams lies at the heart of our mission. We offer skill acquisition and personal development workshops, particularly for women and young adults, equipping them with practical tools for success. Our programs focus on fostering leadership, entrepreneurship, and self-reliance, encouraging individuals to embrace their potential. Through these initiatives, we help people build confidence, develop resilience, and seize opportunities to transform their lives and contribute meaningfully to society.',
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
  