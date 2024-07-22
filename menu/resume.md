<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Resume</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@3.4.1/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100">

  <!-- Hero Section -->
  <section class="bg-gray-900 text-white py-20">
    <div class="container mx-auto px-4">
      <div class="text-center">
        <h1 class="text-4xl font-bold">Hello, I'm John Doe</h1>
        <p class="mt-4">A passionate web developer based in New York City.</p>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section class="py-16">
    <div class="container mx-auto px-4">
      <div class="flex justify-between items-center">
        <div class="w-1/2">
          <h2 class="text-3xl font-bold">About Me</h2>
          <p class="mt-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla quam velit, vulputate eu pharetra nec, mattis ac neque.</p>
        </div>
        <div class="w-1/2">
          <img src="profile.jpg" alt="Profile" class="rounded-full shadow-lg">
        </div>
      </div>
    </div>
  </section>

  <!-- Portfolio Section -->
  <section class="py-16 bg-gray-200">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center">Portfolio</h2>
      <div class="grid grid-cols-3 gap-8 mt-8">
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-bold">Project 1</h3>
          <p class="mt-2">Description of Project 1.</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-bold">Project 2</h3>
          <p class="mt-2">Description of Project 2.</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-bold">Project 3</h3>
          <p class="mt-2">Description of Project 3.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="py-16">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center">Contact Me</h2>
      <form class="mt-8 max-w-md mx-auto">
        <div class="flex flex-wrap mb-4 -mx-2">
          <div class="w-full px-2 mb-4">
            <label for="name" class="block mb-2">Name</label>
            <input type="text" id="name" name="name" class="w-full border-gray-300 rounded-md px-3 py-2 focus:outline-none focus:border-blue-500">
          </div>
          <div class="w-full px-2 mb-4">
            <label for="email" class="block mb-2">Email</label>
            <input type="email" id="email" name="email" class="w-full border-gray-300 rounded-md px-3 py-2 focus:outline-none focus:border-blue-500">
          </div>
          <div class="w-full px-2 mb-4">
            <label for="message" class="block mb-2">Message</label>
            <textarea id="message" name="message" rows="4" class="w-full border-gray-300 rounded-md px-3 py-2 focus:outline-none focus:border-blue-500"></textarea>
          </div>
          <div class="w-full px-2">
            <button type="submit" class="bg-blue-500 text-white py-2 px-4 rounded-md hover:bg-blue-700 focus:outline-none">Send Message</button>
          </div>
        </div>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 text-white py-4">
    <div class="container mx-auto text-center">
      &copy; 2024 My Resume. All rights reserved.
    </div>
  </footer>

</body>
</html>