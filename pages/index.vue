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
                    <img class="w-[80%] absolute top-10" src="https://images.unsplash.com/photo-1726549384638-e530b978ac3e?q=80&w=2069&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="">
                    <img class="w-1/2 absolute top-1 right-1" src="https://images.unsplash.com/photo-1735615479490-237b941e996a?q=80&w=1932&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="">
                    <img class="w-1/2 absolute top-60 right-1" src="https://images.unsplash.com/photo-1734623044490-4bf667aafade?q=80&w=2063&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="">
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
        
        <div class="grid bg-slate-100 py-10 lg:grid-cols-3 gap-10 lg:px-30">
            <div>
                <blockquote class="relative">
                    <svg class="absolute -top-6 -start-8 size-16 text-gray-400" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
                        <path d="M7.39762 10.3C7.39762 11.0733 7.14888 11.7 6.6514 12.18C6.15392 12.6333 5.52552 12.86 4.76621 12.86C3.84979 12.86 3.09047 12.5533 2.48825 11.94C1.91222 11.3266 1.62421 10.4467 1.62421 9.29999C1.62421 8.07332 1.96459 6.87332 2.64535 5.69999C3.35231 4.49999 4.33418 3.55332 5.59098 2.85999L6.4943 4.25999C5.81354 4.73999 5.26369 5.27332 4.84476 5.85999C4.45201 6.44666 4.19017 7.12666 4.05926 7.89999C4.29491 7.79332 4.56983 7.73999 4.88403 7.73999C5.61716 7.73999 6.21938 7.97999 6.69067 8.45999C7.16197 8.93999 7.39762 9.55333 7.39762 10.3ZM14.6242 10.3C14.6242 11.0733 14.3755 11.7 13.878 12.18C13.3805 12.6333 12.7521 12.86 11.9928 12.86C11.0764 12.86 10.3171 12.5533 9.71484 11.94C9.13881 11.3266 8.85079 10.4467 8.85079 9.29999C8.85079 8.07332 9.19117 6.87332 9.87194 5.69999C10.5789 4.49999 11.5608 3.55332 12.8176 2.85999L13.7209 4.25999C13.0401 4.73999 12.4903 5.27332 12.0713 5.85999C11.6786 6.44666 11.4168 7.12666 11.2858 7.89999C11.5215 7.79332 11.7964 7.73999 12.1106 7.73999C12.8437 7.73999 13.446 7.97999 13.9173 8.45999C14.3886 8.93999 14.6242 9.55333 14.6242 10.3Z" fill="currentColor"></path>
                    </svg>

                    <div class="relative z-10">
                        <p class="text-gray-800 sm:text-xl"><em>
                            We are committed to ensuring that every child has access to quality education, regardless of their financial background. Through our scholarship initiatives, we provide opportunities for students who cannot afford schooling, enabling them to pursue their academic goals. Additionally, we distribute educative materials such as books, stationery, and digital learning tools to equip learners with the resources they need to succeed. Our mentorship programs further support students by guiding them toward academic excellence and career achievements, fostering a generation of empowered and knowledgeable individuals.
                        </em></p>
                    </div>
                    </blockquote>
            </div>
            <div>
                <blockquote class="relative">
                    <svg class="absolute -top-6 -start-8 size-16 text-gray-400" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
                        <path d="M7.39762 10.3C7.39762 11.0733 7.14888 11.7 6.6514 12.18C6.15392 12.6333 5.52552 12.86 4.76621 12.86C3.84979 12.86 3.09047 12.5533 2.48825 11.94C1.91222 11.3266 1.62421 10.4467 1.62421 9.29999C1.62421 8.07332 1.96459 6.87332 2.64535 5.69999C3.35231 4.49999 4.33418 3.55332 5.59098 2.85999L6.4943 4.25999C5.81354 4.73999 5.26369 5.27332 4.84476 5.85999C4.45201 6.44666 4.19017 7.12666 4.05926 7.89999C4.29491 7.79332 4.56983 7.73999 4.88403 7.73999C5.61716 7.73999 6.21938 7.97999 6.69067 8.45999C7.16197 8.93999 7.39762 9.55333 7.39762 10.3ZM14.6242 10.3C14.6242 11.0733 14.3755 11.7 13.878 12.18C13.3805 12.6333 12.7521 12.86 11.9928 12.86C11.0764 12.86 10.3171 12.5533 9.71484 11.94C9.13881 11.3266 8.85079 10.4467 8.85079 9.29999C8.85079 8.07332 9.19117 6.87332 9.87194 5.69999C10.5789 4.49999 11.5608 3.55332 12.8176 2.85999L13.7209 4.25999C13.0401 4.73999 12.4903 5.27332 12.0713 5.85999C11.6786 6.44666 11.4168 7.12666 11.2858 7.89999C11.5215 7.79332 11.7964 7.73999 12.1106 7.73999C12.8437 7.73999 13.446 7.97999 13.9173 8.45999C14.3886 8.93999 14.6242 9.55333 14.6242 10.3Z" fill="currentColor"></path>
                    </svg>

                    <div class="relative z-10">
                        <p class="text-gray-800 sm:text-xl"><em>
                            Healthcare is a fundamental right, and we strive to make it accessible to communities in need. The foundation organizes regular outreaches to provide free healthcare services and raise awareness about critical health issues. We supply essential medical provisions and educate communities on hygiene, nutrition, and preventative healthcare practices. By addressing these basic health needs, we aim to build stronger and healthier communities capable of thriving.
                        </em></p>
                    </div>
                    </blockquote>
            </div>
            <div>
                <blockquote class="relative">
                    <svg class="absolute -top-6 -start-8 size-16 text-gray-400" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
                        <path d="M7.39762 10.3C7.39762 11.0733 7.14888 11.7 6.6514 12.18C6.15392 12.6333 5.52552 12.86 4.76621 12.86C3.84979 12.86 3.09047 12.5533 2.48825 11.94C1.91222 11.3266 1.62421 10.4467 1.62421 9.29999C1.62421 8.07332 1.96459 6.87332 2.64535 5.69999C3.35231 4.49999 4.33418 3.55332 5.59098 2.85999L6.4943 4.25999C5.81354 4.73999 5.26369 5.27332 4.84476 5.85999C4.45201 6.44666 4.19017 7.12666 4.05926 7.89999C4.29491 7.79332 4.56983 7.73999 4.88403 7.73999C5.61716 7.73999 6.21938 7.97999 6.69067 8.45999C7.16197 8.93999 7.39762 9.55333 7.39762 10.3ZM14.6242 10.3C14.6242 11.0733 14.3755 11.7 13.878 12.18C13.3805 12.6333 12.7521 12.86 11.9928 12.86C11.0764 12.86 10.3171 12.5533 9.71484 11.94C9.13881 11.3266 8.85079 10.4467 8.85079 9.29999C8.85079 8.07332 9.19117 6.87332 9.87194 5.69999C10.5789 4.49999 11.5608 3.55332 12.8176 2.85999L13.7209 4.25999C13.0401 4.73999 12.4903 5.27332 12.0713 5.85999C11.6786 6.44666 11.4168 7.12666 11.2858 7.89999C11.5215 7.79332 11.7964 7.73999 12.1106 7.73999C12.8437 7.73999 13.446 7.97999 13.9173 8.45999C14.3886 8.93999 14.6242 9.55333 14.6242 10.3Z" fill="currentColor"></path>
                    </svg>

                    <div class="relative z-10">
                        <p class="text-gray-800 sm:text-xl"><em>
                            Empowering individuals to achieve their dreams lies at the heart of our mission. We offer skill acquisition and personal development workshops, particularly for women and young adults, equipping them with practical tools for success. Our programs focus on fostering leadership, entrepreneurship, and self-reliance, encouraging individuals to embrace their potential. Through these initiatives, we help people build confidence, develop resilience, and seize opportunities to transform their lives and contribute meaningfully to society..
                        </em></p>
                    </div>
                    </blockquote>
            </div>
        </div>
    </div>
</template>