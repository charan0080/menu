<script>
	import '../app.css'; 
</script>

<div class="flex flex-col min-h-screen">
  
  <header class="bg-blue-600 text-white p-4 text-center text-xl">
    My Website
  </header>

  <div class="flex flex-1">
    
    <div class="w-1/4 bg-gray-200 p-4">
      <ul class="space-y-2">
        <li><a class="text-blue-500 hover:underline" href="/home">Home</a></li>
        <li><a class="text-blue-500 hover:underline" href="/about">About</a></li>
        <li><a class="text-blue-500 hover:underline" href="/contact">Contact</a></li>
        <li><a class="text-blue-500 hover:underline" href="/courses/online">Courses</a></li>
        <li><a class="text-blue-500 hover:underline" href="/details">details</a></li>
      </ul>
    </div>

    
    <main class="w-3/4 p-6">
      <slot />
    </main>
  </div>

  
  <footer class="bg-blue-600 text-white p-4 text-center">
    2025 My Website
  </footer>
</div>
