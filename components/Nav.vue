<template>
    <header class="text-gray-400 bg-gray-900 body-font lg:px-30 fixed z-[999] top-0 left-0 right-0">
        <div class="grid grid-cols-2 mx-auto  py-5  items-center">
            <NuxtLink to="/" class="w-fit">
            <!-- <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-indigo-500 rounded-full" viewBox="0 0 24 24">
                <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
            </svg> -->
                <span class="ml-3 text-xl">LOGO</span>
            </NuxtLink>
            <nav class="flex flex-wrap items-center text-base justify-end">
                <NuxtLink to="/" class="mr-5 hover:text-white">Home</NuxtLink>
                <NuxtLink to="/who-we-are" class="mr-5 hover:text-white">Who we are</NuxtLink>
                <NuxtLink to="/our-impact" class="mr-5 hover:text-white">Our impact</NuxtLink>
                <SecondaryBtn>Partner with us</SecondaryBtn>
            </nav>
        </div>
    </header>
</template>