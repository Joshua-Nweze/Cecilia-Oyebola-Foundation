<template>
    
    <footer class="bg-white dark:bg-gray-900">
        <div class="mx-auto w-full max-w-screen-xl p-4 py-6 lg:py-8">
            <div class="grid lg:grid-cols-2">
            <NuxtLink to="/" class="mb-6 md:mb-0 text-white">
                <img src="/images/cecy-foundation-logo.png" class="h-40" alt="">
            </NuxtLink>
            <div class="grid grid-cols-2 gap-8">
                <div>
                    <h2 class="mb-6 text-sm font-semibold text-gray-900 uppercase dark:text-white">Links</h2>
                    <ul class="text-gray-500">
                        <li class="mb-4">
                            <NuxtLink to="/">Home</NuxtLink>
                        </li>
                        <li class="mb-4">
                            <NuxtLink to="/who-we-are">Who we are</NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/our-impact">Our impact</NuxtLink>
                        </li>
                    </ul>
                </div>
                <div>
                    <h2 class="mb-6 text-sm font-semibold text-gray-900 uppercase dark:text-white">Contact</h2>
                    <ul class="text-gray-500">
                        <li class="mb-4">
                            <div class="s-p flex gap-3 h-fit">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-6 h-6">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                    d="M3 9.75L12 3l9 6.75V20a1 1 0 01-1 1h-5.25a.75.75 0 01-.75-.75v-4.5a.75.75 0 00-.75-.75H9.75a.75.75 0 00-.75.75v4.5c0 .414-.336.75-.75.75H3.75A.75.75 0 013 20V9.75z" />
                                </svg>
                                <span class="w-5/6">
                                    Cecylian Whitehouse, 12 Kayode Abraham Street, Off Ligali Ayorinde Street, Victoria Island, Lagos State, Nigeria.
                                </span>
                            </div>
                        </li>
                        <li>
                            <div class="s-p flex gap-3 h-fit">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-6 h-6">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                    d="M2.25 4.5C2.25 3.675 2.925 3 3.75 3h1.5c.414 0 .75.336.75.75v2.25a.75.75 0 01-.75.75H4.5v1.5c0 6.075 4.925 11 11 11h1.5v-1.5a.75.75 0 01.75-.75h2.25a.75.75 0 01.75.75v1.5c0 .825-.675 1.5-1.5 1.5h-3A15.75 15.75 0 012.25 4.5z" />
                                </svg>
                                <div>
                                    <a href="tel:+09131058071">0913 105 8071</a>
                                </div>
                            </div>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
        <hr class="my-6 border-gray-200 sm:mx-auto dark:border-gray-700 lg:my-8" />
        <div class="sm:flex sm:items-center sm:justify-between">
            <span class="text-sm text-gray-500 sm:text-center dark:text-gray-400">© {{ new Date().getFullYear() }} Cecelia Oyebola Foundation. All Rights Reserved.
            </span>
            <!-- <div class="flex mt-4 sm:justify-center sm:mt-0">
                <a href="#" class="text-gray-500 hover:text-gray-900 dark:hover:text-white">
                    <svg class="w-4 h-4" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 8 19">
                            <path fill-rule="evenodd" d="M6.135 3H8V0H6.135a4.147 4.147 0 0 0-4.142 4.142V6H0v3h2v9.938h3V9h2.021l.592-3H5V3.591A.6.6 0 0 1 5.592 3h.543Z" clip-rule="evenodd"/>
                        </svg>
                    <span class="sr-only">Facebook page</span>
                </a>
                <a href="#" class="text-gray-500 hover:text-gray-900 dark:hover:text-white ms-5">
                    <svg class="w-4 h-4" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 17">
                        <path fill-rule="evenodd" d="M20 1.892a8.178 8.178 0 0 1-2.355.635 4.074 4.074 0 0 0 1.8-2.235 8.344 8.344 0 0 1-2.605.98A4.13 4.13 0 0 0 13.85 0a4.068 4.068 0 0 0-4.1 4.038 4 4 0 0 0 .105.919A11.705 11.705 0 0 1 1.4.734a4.006 4.006 0 0 0 1.268 5.392 4.165 4.165 0 0 1-1.859-.5v.05A4.057 4.057 0 0 0 4.1 9.635a4.19 4.19 0 0 1-1.856.07 4.108 4.108 0 0 0 3.831 2.807A8.36 8.36 0 0 1 0 14.184 11.732 11.732 0 0 0 6.291 16 11.502 11.502 0 0 0 17.964 4.5c0-.177 0-.35-.012-.523A8.143 8.143 0 0 0 20 1.892Z" clip-rule="evenodd"/>
                    </svg>
                    <span class="sr-only">Twitter page</span>
                </a>
            </div> -->
        </div>
        </div>
    </footer>

</template>