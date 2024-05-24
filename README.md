<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chat UI</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #1e1e1e;
        }
    </style>
</head>
<body class="flex justify-center items-center h-screen">
    <div class="w-full max-w-4xl bg-gray-900 text-gray-200 rounded-lg overflow-hidden shadow-lg">
        <div class="flex flex-col h-full">
            <!-- Sidebar -->
            <div class="flex flex-none bg-gray-800 p-4">
                <div class="flex-grow">
                    <input type="text" placeholder="Search" class="w-full bg-gray-700 text-gray-300 rounded-lg px-3 py-2 focus:outline-none focus:ring-2 focus:ring-indigo-600">
                </div>
            </div>
            <div class="flex flex-1 overflow-y-hidden">
                <div class="w-1/4 bg-gray-800 overflow-y-auto">
                    <ul>
                        <li class="p-4 border-b border-gray-700">
                            <span class="block font-semibold">ABNY Team 🛠️</span>
                            <span class="text-sm text-gray-400">You: Ok bhaiya</span>
                        </li>
                        <li class="p-4 border-b border-gray-700">
                            <span class="block font-semibold">Information</span>
                            <span class="text-sm text-gray-400">Stephen Barabanki SVC: Thank you bhaiya</span>
                        </li>
                        <li class="p-4 border-b border-gray-700">
                            <span class="block font-semibold">Dua Villa Folks ☕</span>
                            <span class="text-sm text-gray-400">Samson Bhaiya: Cfl</span>
                        </li>
                        <li class="p-4 border-b border-gray-700">
                            <span class="block font-semibold">Sandeep Bhaiya Abny</span>
                            <span class="text-sm text-gray-400">FTT@.xlsx</span>
                        </li>
                        <li class="p-4 border-b border-gray-700">
                            <span class="block font-semibold">2RSYP.G. college2ndsem(sociology)</span>
                            <span class="text-sm text-gray-400">Bhupendra Singh: सूचना ===== सभी छात्र/छात्राएँ अपना प्रोजेक्ट भ...</span>
                        </li>
                        <li class="p-4 border-b border-gray-700">
                            <span class="block font-semibold">EIC Videos/Graphics</span>
                            <span class="text-sm text-gray-400">M@R!0: Sweet</span>
                        </li>
                        <li class="p-4 border-b border-gray-700">
                            <span class="block font-semibold">WORK ABNY</span>
                            <span class="text-sm text-gray-400">Sandeep: Bhaiya, I will be working on...</span>
                        </li>
                        <li class="p-4 border-b border-gray-700">
                            <span class="block font-semibold">Prince Bhai SVC</span>
                            <span class="text-sm text-gray-400">C: opened</span>
                        </li>
                        <li class="p-4 border-b border-gray-700">
                            <span class="block font-semibold">Kundan Singh SVC</span>
                        </li>
                    </ul>
                </div>
                <!-- Chat Section -->
                <div class="flex flex-col flex-1 bg-gray-900">
                    <div class="p-4 flex-none bg-gray-800 flex items-center">
                        <span class="font-semibold">ABNY Team 🛠️</span>
                    </div>
                    <div class="flex-1 p-4 overflow-y-auto">
                        <div class="flex flex-col space-y-4">
                            <div class="flex">
                                <div class="bg-gray-700 p-4 rounded-lg">
                                    <p class="text-sm">Ashish John Bhaiya</p>
                                    <p class="mt-2">Bal Govind Bhai please keep his details</p>
                                </div>
                            </div>
                            <div class="flex">
                                <div class="bg-gray-700 p-4 rounded-lg">
                                    <p class="text-sm">Ashish John Bhaiya</p>
                                    <p class="mt-2">mariokp.wixsite.com<br>https://mariokp.wixsite.com/mariopeter<br>Bhai please keep his projects on design' section</p>
                                </div>
                            </div>
                            <div class="flex">
                                <div class="bg-gray-700 p-4 rounded-lg">
                                    <p class="text-sm">Ashish John Bhaiya</p>
                                    <img src="https://via.placeholder.com/150" alt="Image" class="mt-2 rounded-lg">
                                    <p class="mt-2">And keep these categories according to the pictures</p>
                                    <p class="mt-2">maybe you can use Accordion or Tabs</p>
                                </div>
                            </div>
                            <div class="flex justify-end">
                                <img src="https://via.placeholder.com/150" alt="Image" class="rounded-lg">
                            </div>
                        </div>
                    </div>
                    <div class="flex-none p-4 bg-gray-800">
                        <input type="text" placeholder="Type a message" class="w-full bg-gray-700 text-gray-300 rounded-lg px-3 py-2 focus:outline-none focus:ring-2 focus:ring-indigo-600">
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
