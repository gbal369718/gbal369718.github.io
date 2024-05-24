<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bal Govind - Web Developer</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-900 text-white">
    <!-- Header -->
    <header class="bg-gray-800 py-4">
        <div class="container mx-auto px-4">
            <h1 class="text-4xl font-bold">Bal Govind</h1>
            <p class="mt-2 text-lg">Web Developer</p>
        </div>
    </header>

    <!-- About Section -->
    <section id="about" class="py-12">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-semibold">About Me</h2>
            <p class="mt-4 text-gray-300">
                Hello! I'm Bal Govind, a passionate web developer with experience in building responsive and interactive websites using modern technologies. I enjoy creating clean, efficient, and user-friendly websites that provide value to users.
            </p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-12 bg-gray-800">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-semibold">Projects</h2>
            <div class="mt-8 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="bg-gray-700 p-6 rounded-lg">
                    <img src="https://via.placeholder.com/300x200" alt="Project 1" class="rounded-lg mb-4">
                    <h3 class="text-xl font-semibold">Project 1</h3>
                    <p class="mt-2 text-gray-300">Description of project 1. This project showcases my skills in HTML, CSS, and JavaScript.</p>
                </div>
                <!-- Project 2 -->
                <div class="bg-gray-700 p-6 rounded-lg">
                    <img src="https://via.placeholder.com/300x200" alt="Project 2" class="rounded-lg mb-4">
                    <h3 class="text-xl font-semibold">Project 2</h3>
                    <p class="mt-2 text-gray-300">Description of project 2. This project demonstrates my ability to create responsive layouts.</p>
                </div>
                <!-- Project 3 -->
                <div class="bg-gray-700 p-6 rounded-lg">
                    <img src="https://via.placeholder.com/300x200" alt="Project 3" class="rounded-lg mb-4">
                    <h3 class="text-xl font-semibold">Project 3</h3>
                    <p class="mt-2 text-gray-300">Description of project 3. This project highlights my proficiency in backend development.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-12">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-semibold">Contact Me</h2>
            <p class="mt-4 text-gray-300">Feel free to get in touch with me through the form below:</p>
            <form action="#" method="POST" class="mt-8 max-w-lg mx-auto">
                <div class="mb-4">
                    <label for="name" class="block text-gray-400">Name</label>
                    <input type="text" id="name" name="name" class="w-full bg-gray-700 text-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-indigo-600">
                </div>
                <div class="mb-4">
                    <label for="email" class="block text-gray-400">Email</label>
                    <input type="email" id="email" name="email" class="w-full bg-gray-700 text-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-indigo-600">
                </div>
                <div class="mb-4">
                    <label for="message" class="block text-gray-400">Message</label>
                    <textarea id="message" name="message" rows="4" class="w-full bg-gray-700 text-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-indigo-600"></textarea>
                </div>
                <button type="submit" class="w-full bg-indigo-600 text-white rounded-lg px-4 py-2 hover:bg-indigo-500 focus:outline-none focus:ring-2 focus:ring-indigo-600">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 py-4">
        <div class="container mx-auto px-4 text-center">
            <p class="text-gray-400">&copy; 2024 Bal Govind. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
