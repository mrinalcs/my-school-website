<nav class="bg-white border-gray-200 dark:bg-gray-900">
    <div class="flex flex-wrap justify-between items-center mx-auto max-w-screen-xl p-4">
        <a href="/" class="flex items-center">
            <img src="/img/visva-bharati-logo.jpg" class="h-8 mr-3" alt="Flowbite Logo" />
            <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white">Department of Statistics</span>
        </a>
        <div class="flex items-center">
            <a href="tel:5541251234" class="mr-6 text-sm  text-gray-500 dark:text-white hover:underline">(555) 412-1234</a>
            <a href="#" class="text-sm  text-blue-600 dark:text-blue-500 hover:underline">Login</a>
        </div>
    </div>
</nav>
    <nav class="bg-gray-50 dark:bg-gray-700"  style="white-space: nowrap;">
        <div class="max-w-screen-xl px-4 py-3 mx-auto">
            <div class="flex items-center">
                <ul class="flex flex-row font-medium mt-0 mr-6 space-x-8 text-sm">
                    <li class="relative">
                        <a href="/" class="text-gray-900 dark:text-white hover:underline" aria-current="page">HOME</a>
                    </li>
                    <li class="relative">
                        <a href="/about-department" class="text-gray-900 dark:text-white hover:underline">ABOUT US</a>
                        <ul class="absolute hidden mt-2 space-y-2 bg-white dark:bg-gray-900 text-gray-900 dark:text-white border border-gray-200 dark:border-gray-700 rounded-lg">
                            <li><a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-800">Submenu Item 1</a></li>
                            <li><a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-800">Submenu Item 2</a></li>
                        </ul>
                    </li>
                    <li class="relative">
                        <a href="/programmes" class="text-gray-900 dark:text-white hover:underline">PROGRAMMES</a>
                        <ul class="absolute hidden mt-2 space-y-2 bg-white dark:bg-gray-900 text-gray-900 dark:text-white border border-gray-200 dark:border-gray-700 rounded-lg">
                            <li><a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-800">Submenu Item 1</a></li>
                            <li><a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-800">Submenu Item 2</a></li>
                        </ul>
                    </li>
                    <li class="relative">
                        <a href="/admission" class="text-gray-900 dark:text-white hover:underline">ADMISSION</a>
                    </li>
                    <li class="relative">
                        <a href="/people" class="text-gray-900 dark:text-white hover:underline">PEOPLE</a>
                    </li>
                    <li class="relative">
                        <a href="/research" class="text-gray-900 dark:text-white hover:underline">RESEARCH</a>
                    </li>
                    <li class="relative">
                        <a href="/academic-calendar" class="text-gray-900 dark:text-white hover:underline">ACADEMIC CALENDAR</a>
                    </li>
                    <li class="relative">
                        <a href="/events" class="text-gray-900 dark:text-white hover:underline">EVENTS</a>
                    </li>
                    <li class="relative">
                        <a href="/notices" class="text-gray-900 dark:text-white hover:underline relative">NOTICES</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>








 
 <style>
        /* CSS for Dropdown Menu */
        nav ul ul {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            background-color: #fff;
            border: 1px solid #ccc;
            border-radius: 4px;
            z-index: 1;
        }

        nav ul li:hover > ul {
            display: block;
        }

        nav ul ul li {
            width: 100%;
        }

        nav ul ul a {
            padding: 10px 20px;
            color: #333;
            text-decoration: none;
            display: block;
        }

        nav ul ul a:hover {
            background-color: #f4f4f4;
        }
    </style>

     <script>
        // JavaScript for Dropdown Menu
        document.addEventListener("DOMContentLoaded", function () {
            const dropdownToggles = document.querySelectorAll("nav ul li");

            dropdownToggles.forEach((toggle) => {
                let timer; // Variable to store a timer

                toggle.addEventListener("mouseenter", function () {
                    const submenu = this.querySelector("ul");
                    if (submenu) {
                        clearTimeout(timer); // Clear any previous timer
                        submenu.style.display = "block";
                    }
                });

                toggle.addEventListener("mouseleave", function () {
                    const submenu = this.querySelector("ul");
                    if (submenu) {
                        // Set a timer to hide the submenu after 300 milliseconds (adjust as needed)
                        timer = setTimeout(() => {
                            submenu.style.display = "none";
                        }, 300);
                    }
                });
            });
        });
    </script>