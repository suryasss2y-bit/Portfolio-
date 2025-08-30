<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Surya | Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-900">

  <!-- Navbar -->
  <header class="bg-white shadow-md sticky top-0 z-50">
    <div class="container mx-auto flex justify-between items-center p-4">
      <h1 class="text-2xl font-bold text-indigo-600">Surya</h1>
      <nav class="space-x-6">
        <a href="#about" class="hover:text-indigo-600">About</a>
        <a href="#skills" class="hover:text-indigo-600">Skills</a>
        <a href="#projects" class="hover:text-indigo-600">Projects</a>
        <a href="#contact" class="hover:text-indigo-600">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="text-center py-20 bg-gradient-to-r from-indigo-500 to-purple-600 text-white">
    <h2 class="text-4xl font-bold mb-4">Hi, I'm Surya 👋</h2>
    <p class="text-lg mb-6">Frontend Developer | Aspiring Full-Stack Engineer</p>
    <a href="#projects" class="bg-white text-indigo-600 px-6 py-2 rounded-full font-semibold shadow hover:bg-gray-200">View My Work</a>
  </section>

  <!-- About Section -->
  <section id="about" class="container mx-auto py-16 px-6">
    <h2 class="text-3xl font-bold mb-6 text-center">About Me</h2>
    <p class="text-center max-w-2xl mx-auto text-gray-700">
      I am Surya, passionate about web development and constantly learning new technologies. 
      I enjoy building responsive and user-friendly websites with clean design and smooth functionality.
    </p>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="bg-gray-50 py-16">
    <div class="container mx-auto px-6">
      <h2 class="text-3xl font-bold mb-10 text-center">Skills</h2>
      <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-6 text-center">
        <div class="p-4 bg-white shadow rounded-lg">HTML5</div>
        <div class="p-4 bg-white shadow rounded-lg">CSS3</div>
        <div class="p-4 bg-white shadow rounded-lg">JavaScript</div>
        <div class="p-4 bg-white shadow rounded-lg">Tailwind CSS</div>
        <div class="p-4 bg-white shadow rounded-lg">React.js</div>
        <div class="p-4 bg-white shadow rounded-lg">Python</div>
        <div class="p-4 bg-white shadow rounded-lg">MySQL</div>
        <div class="p-4 bg-white shadow rounded-lg">Django</div>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="container mx-auto py-16 px-6">
    <h2 class="text-3xl font-bold mb-10 text-center">Projects</h2>
    <div class="grid md:grid-cols-3 gap-6">
      <div class="bg-white shadow rounded-lg p-4">
        <h3 class="text-xl font-semibold mb-2">Portfolio Website</h3>
        <p class="text-gray-600">A responsive portfolio website built with Tailwind CSS.</p>
      </div>
      <div class="bg-white shadow rounded-lg p-4">
        <h3 class="text-xl font-semibold mb-2">ToDo App</h3>
        <p class="text-gray-600">A task manager app made with JavaScript and local storage.</p>
      </div>
      <div class="bg-white shadow rounded-lg p-4">
        <h3 class="text-xl font-semibold mb-2">Blog Platform</h3>
        <p class="text-gray-600">A full-stack blog with Django backend and MySQL database.</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="bg-gradient-to-r from-indigo-500 to-purple-600 py-16 text-white text-center">
    <h2 class="text-3xl font-bold mb-6">Get In Touch</h2>
    <p class="mb-6">Feel free to reach out for collaborations or just a friendly hello!</p>
    <a href="mailto:surya@example.com" class="bg-white text-indigo-600 px-6 py-2 rounded-full font-semibold shadow hover:bg-gray-200">Say Hello</a>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-gray-400 py-6 text-center">
    © 2025 Surya. All Rights Reserved.
  </footer>

</body>
</html>
<style>
  .btn-glow {
    position: relative;
    overflow: hidden;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  .btn-glow::before {
    content: "";
    position: absolute;
    top: -50%;
    left: -50%;
    width: 200%;
    height: 200%;
    background: radial-gradient(circle, rgba(255,255,255,0.3) 0%, transparent 80%);
    transform: rotate(45deg);
    animation: glowMove 3s linear infinite;
  }

  @keyframes glowMove {
    0% {
      transform: translateX(-100%) rotate(45deg);
    }
    100% {
      transform: translateX(100%) rotate(45deg);
    }
  }

  .btn-glow:hover {
    box-shadow: 0 0 20px rgba(255,255,255,0.7);
    transform: scale(1.05);
  }
</style>
<a href="mailto:suryasss2y@gmail.com"
   class="bg-white text-indigo-600 px-6 py-2 rounded-full font-semibold shadow hover:bg-gray-200 btn-lighting">
   Say Hello
</a>
