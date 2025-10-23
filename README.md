<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gordon's Special Cuts - Our Selection</title>
    <!-- Imports Tailwind CSS for styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Applies the Inter font to the whole page */
        body {
            font-family: 'Inter', sans-serif;
        }
        /* You can preload fonts if you host them, but for a CDN this is fine */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
    </style>
</head>
<body class="bg-gray-50">

    <!-- Header Section -->
    <header class="bg-white shadow-md sticky top-0 z-10">
        <nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <!-- Logo/Store Name -->
                <div class="flex-shrink-0">
                    <h1 class="text-3xl font-bold text-red-800">Gordon's Special Cuts</h1>
                </div>
                <!-- Navigation Links -->
                <div class="hidden md:block">
                    <div class="ml-10 flex items-baseline space-x-4">
                        <a href="#" class="bg-red-700 text-white px-3 py-2 rounded-md text-sm font-medium">Our Cuts</a>
                        <a href="#" class="text-gray-600 hover:bg-gray-100 hover:text-gray-900 px-3 py-2 rounded-md text-sm font-medium">About Us</a>
                        <a href="#" class="text-gray-600 hover:bg-gray-100 hover:text-gray-900 px-3 py-2 rounded-md text-sm font-medium">Contact</a>
                    </div>
                </div>
                <!-- Mobile Menu Button (visual only) -->
                <div class="-mr-2 flex md:hidden">
                    <button type="button" class="bg-gray-100 inline-flex items-center justify-center p-2 rounded-md text-gray-500 hover:text-gray-800 hover:bg-gray-200" aria-controls="mobile-menu" aria-expanded="false">
                        <span class="sr-only">Open main menu</span>
                        <!-- Icon for menu (hamburger) -->
                        <svg class="block h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                        </svg>
                    </button>
                </div>
            </div>
        </nav>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Hero Section -->
        <div class="bg-red-800">
            <div class="max-w-7xl mx-auto py-16 px-4 text-center sm:px-6 lg:px-8">
                <h2 class="text-4xl font-extrabold text-white sm:text-5xl">
                    Artisan Cuts. Peak Quality.
                </h2>
                <p class="mt-4 text-xl text-red-100">
                    Discover our selection of premium, hand-selected meats, cut specially for you.
                </p>
            </div>
        </div>

        <!-- Product Grid Section -->
        <div class="max-w-7xl mx-auto py-16 px-4 sm:px-6 lg:px-8">
            <h3 class="text-3xl font-bold text-gray-900 text-center mb-12">Our Special Cuts</h3>

            <!-- This is the grid that holds the product cards -->
            <!-- It's 1 column on mobile, 2 on tablets, and 3 on desktops -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">

                <!-- Product Card 1 -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden transform transition duration-300 hover:scale-105">
                    <img class="h-64 w-full object-cover" 
                         src="https://placehold.co/600x400/8c2d2d/ffffff?text=Dry-Aged+Tomahawk" 
                         alt="Dry-Aged Tomahawk Steak"
                         onerror="this.src='https://placehold.co/600x400/8c2d2d/ffffff?text=Image+Not+Found'">
                    <div class="p-6">
                        <h4 class="text-2xl font-bold text-gray-800">45-Day Dry-Aged Tomahawk</h4>
                        <p class="text-gray-600 mt-2">A true showstopper. Aged for maximum flavor and tenderness. Sold by the steak (approx 2.5 lbs).</p>
                        <div class="mt-4 flex justify-between items-center">
                            <span class="text-3xl font-light text-red-700">$42.50 / lb</span>
                            <a href="#" class="bg-red-600 text-white py-2 px-4 rounded-lg font-semibold hover:bg-red-700 transition">Order Now</a>
                        </div>
                    </div>
                </div>

                <!-- Product Card 2 -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden transform transition duration-300 hover:scale-105">
                    <img class="h-64 w-full object-cover" 
                         src="https://placehold.co/600x400/a64a4a/ffffff?text=Wagyu+Brisket" 
                         alt="Wagyu Brisket"
                         onerror="this.src='https://placehold.co/600x400/a64a4a/ffffff?text=Image+Not+Found'">
                    <div class="p-6">
                        <h4 class="text-2xl font-bold text-gray-800">A5 Wagyu Brisket</h4>
                        <p class="text-gray-600 mt-2">Incredible marbling for the ultimate smoker experience. This is the best you can get.</p>
                        <div class="mt-4 flex justify-between items-center">
                            <span class="text-3xl font-light text-red-700">$28.99 / lb</span>
                            <a href="#" class="bg-red-600 text-white py-2 px-4 rounded-lg font-semibold hover:bg-red-700 transition">Order Now</a>
                        </div>
                    </div>
                </div>

                <!-- Product Card 3 -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden transform transition duration-300 hover:scale-105">
                    <img class="h-64 w-full object-cover" 
                         src="https://placehold.co/600x400/6b2e2e/ffffff?text=Pork+Belly" 
                         alt="Berkshire Pork Belly"
                         onerror="this.src='https://placehold.co/600x400/6b2e2e/ffffff?text=Image+Not+Found'">
                    <div class="p-6">
                        <h4 class="text-2xl font-bold text-gray-800">Berkshire Pork Belly</h4>
                        <p class="text-gray-600 mt-2">Rich, flavorful, and incredibly versatile. Perfect for roasting, braising, or curing your own bacon.</p>
                        <div class="mt-4 flex justify-between items-center">
                            <span class="text-3xl font-light text-red-700">$14.99 / lb</span>
                            <a href="#" class="bg-red-600 text-white py-2 px-4 rounded-lg font-semibold hover:bg-red-700 transition">Order Now</a>
                        </div>
                    </div>
                </div>

                <!-- Product Card 4 -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden transform transition duration-300 hover:scale-105">
                    <img class="h-64 w-full object-cover" 
                         src="https://placehold.co/600x400/9b4444/ffffff?text=Lamb+Roast" 
                         alt="Lamb Crown Roast"
                         onerror="this.src='https://placehold.co/600x400/9b4444/ffffff?text=Image+Not+Found'">
                    <div class="p-6">
                        <h4 class="text-2xl font-bold text-gray-800">Lamb Crown Roast</h4>
                        <p class="text-gray-600 mt-2">An elegant centerpiece for any special occasion. Tender, juicy, and packed with delicate flavor.</p>
                        <div class="mt-4 flex justify-between items-center">
                            <span class="text-3xl font-light text-red-700">$34.99 / lb</span>
                            <a href="#" class="bg-red-600 text-white py-2 px-4 rounded-lg font-semibold hover:bg-red-700 transition">Order Now</a>
                        </div>
                    </div>
                </div>

                <!-- Product Card 5 -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden transform transition duration-300 hover:scale-105">
                    <img class="h-64 w-full object-cover" 
                         src="https://placehold.co/600x400/b55a5a/ffffff?text=Chorizo" 
                         alt="House-Made Chorizo"
                         onerror="this.src='https://placehold.co/600x400/b55a5a/ffffff?text=Image+Not+Found'">
                    <div class="p-6">
                        <h4 class="text-2xl font-bold text-gray-800">House-Made Chorizo</h4>
                        <p class="text-gray-600 mt-2">Our signature blend of premium pork and smoked paprika. Smoky, savory, and perfectly spiced.</p>
                        <div class="mt-4 flex justify-between items-center">
                            <span class="text-3xl font-light text-red-700">$12.99 / lb</span>
                            <a href="#" class="bg-red-600 text-white py-2 px-4 rounded-lg font-semibold hover:bg-red-700 transition">Order Now</a>
                        </div>
                    </div>
                </div>

                <!-- Product Card 6 -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden transform transition duration-300 hover:scale-105">
                    <img class="h-64 w-full object-cover" 
                         src="https://placehold.co/600x400/7a3a3a/ffffff?text=Venison+Loin" 
                         alt="Venison Loin"
                         onerror="this.src='https://placehold.co/600x400/7a3a3a/ffffff?text=Image+Not+Found'">
                    <div class="p-6">
                        <h4 class="text-2xl font-bold text-gray-800">Wild Venison Loin</h4>
                        <p class="text-gray-600 mt-2">A lean, wild-game delicacy. Deep, rich flavor with a tender bite. Perfect for a quick sear.</p>
                        <div class="mt-4 flex justify-between items-center">
                            <span class="text-3xl font-light text-red-700">$39.99 / lb</span>
                            <a href="#" class="bg-red-600 text-white py-2 px-4 rounded-lg font-semibold hover:bg-red-700 transition">Order Now</a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800">
        <div class="max-w-7xl mx-auto py-12 px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-2xl font-bold text-white">Gordon's Special Cuts</h2>
            <p class="mt-2 text-gray-400">Quality meat, delivered right to your door.</p>
            <div class="mt-6 flex justify-center space-x-6">
                <!-- Social media icons (placeholders) -->
                <a href="#" class="text-gray-400 hover:text-white">
                    <span class="sr-only">Instagram</span>
                    <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                        <!-- Instagram Icon Path -->
                        <path fill-rule="evenodd" d="M12 2C6.477 2 2 6.477 2 12s4.477 10 10 10 10-4.477 10-10S17.523 2 12 2zm3.207 13.793a1 1 0 01-1.414 0L12 13.414l-1.793 1.793a1 1 0 01-1.414-1.414L10.586 12l-1.793-1.793a1 1 0 111.414-1.414L12 10.586l1.793-1.793a1 1 0 111.414 1.414L13.414 12l1.793 1.793a1 1 0 010 1.414z" clip-rule="evenodd" />
                    </svg>
                </a>
                <a href="#" class="text-gray-400 hover:text-white">
                    <span class="sr-only">Facebook</span>
                    <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                        <!-- Facebook Icon Path -->
                        <path fill-rule="evenodd" d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z" clip-rule="evenodd" />
                    </svg>
                </a>
            </div>
            <p class="mt-8 text-base text-gray-500">
                &copy; 2025 Gordon's Special Cuts. All rights reserved.
            </p>
        </div>
    </footer>

</body>
</html>

