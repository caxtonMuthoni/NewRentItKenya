<template>
    <div
        class="min-h-screen bg-gradient-to-br from-blue-50 to-indigo-100 flex flex-col items-center justify-center p-6"
    >
        <div
            class="max-w-4xl w-full bg-white rounded-xl shadow-xl overflow-hidden"
        >
            <!-- Header -->
            <div class="bg-indigo-600 p-8 text-center">
                <h1 class="text-4xl font-bold text-white mb-2">Coming Soon</h1>
                <p class="text-indigo-100 text-xl">
                    Our Property Management System is Under Development
                </p>
            </div>

            <!-- Content -->
            <div class="p-8 md:p-12 flex flex-col md:flex-row items-center">
                <!-- Illustration -->
                <div class="md:w-1/2 mb-8 md:mb-0 md:pr-8">
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        viewBox="0 0 512 512"
                        class="w-full h-auto"
                    >
                        <defs>
                            <linearGradient
                                id="a"
                                x1="256"
                                x2="256"
                                y2="512"
                                gradientUnits="userSpaceOnUse"
                            >
                                <stop offset="0" stop-color="#818cf8" />
                                <stop offset="1" stop-color="#4f46e5" />
                            </linearGradient>
                        </defs>
                        <path
                            fill="url(#a)"
                            d="M256 0c-17.7 0-32 14.3-32 32v32h64V32c0-17.7-14.3-32-32-32z"
                        />
                        <path
                            fill="#c7d2fe"
                            d="M416 192c0-17.7-14.3-32-32-32H128c-17.7 0-32 14.3-32 32v256c0 17.7 14.3 32 32 32h256c17.7 0 32-14.3 32-32V192z"
                        />
                        <path
                            fill="#e0e7ff"
                            d="M96 160c0-17.7 14.3-32 32-32h256c17.7 0 32 14.3 32 32v32H96v-32z"
                        />
                        <path
                            fill="#4f46e5"
                            d="M160 256a32 32 0 1 1 0 64 32 32 0 1 1 0-64zm0 96a32 32 0 1 1 0 64 32 32 0 1 1 0-64zm96-96a32 32 0 1 1 0 64 32 32 0 1 1 0-64zm0 96a32 32 0 1 1 0 64 32 32 0 1 1 0-64zm96-96a32 32 0 1 1 0 64 32 32 0 1 1 0-64zm0 96a32 32 0 1 1 0 64 32 32 0 1 1 0-64z"
                        />
                        <path
                            fill="#6366f1"
                            d="M384 128c17.7 0 32-14.3 32-32V32c0-17.7-14.3-32-32-32h-32v128h32zM128 0H96c-17.7 0-32 14.3-32 32v64c0 17.7 14.3 32 32 32h32V0z"
                        />
                    </svg>
                </div>

                <!-- Text Content -->
                <div class="md:w-1/2">
                    <h2 class="text-2xl font-bold text-gray-800 mb-4">
                        Something Amazing is Coming
                    </h2>
                    <p class="text-gray-600 mb-6">
                        We're working hard to build a comprehensive Property
                        Management System that will revolutionize how you manage
                        your properties. Expect powerful tools for tenant
                        management, maintenance tracking, financial reporting,
                        and much more.
                    </p>

                    <div class="mb-8">
                        <h3 class="font-semibold text-indigo-600 mb-2">
                            Features to look forward to:
                        </h3>
                        <ul class="space-y-2">
                            <li class="flex items-start">
                                <svg
                                    class="h-5 w-5 text-green-500 mr-2 mt-0.5"
                                    fill="none"
                                    viewBox="0 0 24 24"
                                    stroke="currentColor"
                                >
                                    <path
                                        stroke-linecap="round"
                                        stroke-linejoin="round"
                                        stroke-width="2"
                                        d="M5 13l4 4L19 7"
                                    />
                                </svg>
                                <span>Tenant and lease management</span>
                            </li>
                            <li class="flex items-start">
                                <svg
                                    class="h-5 w-5 text-green-500 mr-2 mt-0.5"
                                    fill="none"
                                    viewBox="0 0 24 24"
                                    stroke="currentColor"
                                >
                                    <path
                                        stroke-linecap="round"
                                        stroke-linejoin="round"
                                        stroke-width="2"
                                        d="M5 13l4 4L19 7"
                                    />
                                </svg>
                                <span>Maintenance request tracking</span>
                            </li>
                            <li class="flex items-start">
                                <svg
                                    class="h-5 w-5 text-green-500 mr-2 mt-0.5"
                                    fill="none"
                                    viewBox="0 0 24 24"
                                    stroke="currentColor"
                                >
                                    <path
                                        stroke-linecap="round"
                                        stroke-linejoin="round"
                                        stroke-width="2"
                                        d="M5 13l4 4L19 7"
                                    />
                                </svg>
                                <span>Automated rent collection</span>
                            </li>
                            <li class="flex items-start">
                                <svg
                                    class="h-5 w-5 text-green-500 mr-2 mt-0.5"
                                    fill="none"
                                    viewBox="0 0 24 24"
                                    stroke="currentColor"
                                >
                                    <path
                                        stroke-linecap="round"
                                        stroke-linejoin="round"
                                        stroke-width="2"
                                        d="M5 13l4 4L19 7"
                                    />
                                </svg>
                                <span>Financial reporting and analytics</span>
                            </li>
                        </ul>
                    </div>

                    <!-- Countdown or Progress -->
                    <div class="mb-6">
                        <div
                            class="flex justify-between text-sm text-gray-600 mb-1"
                        >
                            <span>Development Progress</span>
                            <span>1%</span>
                        </div>
                        <div class="w-full bg-gray-200 rounded-full h-2.5">
                            <div
                                class="bg-indigo-600 h-2.5 rounded-full"
                                style="width: 1%"
                            ></div>
                        </div>
                    </div>

                    <!-- Notify Me Button -->
                    <div class="fle flex-col sm:flex-row gap-3 hidden">
                        <input
                            type="email"
                            placeholder="Enter your email"
                            class="flex-grow px-4 py-2 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-indigo-500"
                        />
                        <button
                            class="bg-indigo-600 hover:bg-indigo-700 text-white font-medium py-2 px-6 rounded-lg transition duration-200"
                        >
                            Notify Me
                        </button>
                    </div>
                </div>
            </div>

            <!-- Footer -->
            <div class="bg-gray-50 px-8 py-4 text-center text-gray-500 text-sm">
                © {{ new Date().getFullYear() }} RentItKenya. All rights
                reserved.
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "UnderDevelopment",
};
</script>
