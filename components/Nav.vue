<template>
    <header class="text-gray-400 bg-gray-900 body-font lg:px-30 fixed z-[999] top-0 left-0 right-0">
        <div class="grid grid-cols-2 mx-auto py-1 items-center">
            <NuxtLink to="/" class="w-fit">
                <img src="/images/cecy-foundation-logo.png" class="h-20" alt="">
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