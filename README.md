<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>H.U Store | All-in-One Online Shopping</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Inter', sans-serif; }
    .gradient-bg { background: linear-gradient(to right, #6366f1, #8b5cf6); }
  </style>
</head>
<body class="bg-gray-50 text-gray-800">
  <header class="bg-white shadow-md sticky top-0 z-50">
    <div class="max-w-7xl mx-auto px-4 py-5 flex justify-between items-center">
      <h1 class="text-3xl font-extrabold text-indigo-600 tracking-wide">H.U Store</h1>
      <nav>
        <ul class="flex gap-6 text-sm font-semibold text-gray-700">
          <li><a href="#shop" class="hover:text-indigo-600 transition">Shop</a></li>
          <li><a href="#about" class="hover:text-indigo-600 transition">About</a></li>
          <li><a href="#contact" class="hover:text-indigo-600 transition">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="text-center py-20 gradient-bg text-white">
    <h2 class="text-5xl font-extrabold mb-4">Welcome to H.U Store 🛍️</h2>
    <p class="text-xl mb-6">Your one-stop shop for quality products at unbeatable prices</p>
    <a href="#shop" class="bg-white text-indigo-600 font-bold px-8 py-3 rounded-full shadow-lg hover:bg-gray-100 transition">Start Shopping</a>
  </section>

  <section id="shop" class="max-w-7xl mx-auto py-20 px-4">
    <h3 class="text-3xl font-bold mb-10 text-center text-indigo-600">Featured Products</h3>
    <div class="grid md:grid-cols-3 sm:grid-cols-2 gap-8">
      <!-- Product Card Example -->
      <div class="bg-white rounded-2xl shadow-lg overflow-hidden transition transform hover:scale-105">
        <img src="https://via.placeholder.com/300" alt="Product" class="w-full h-56 object-cover">
        <div class="p-5">
          <h4 class="font-semibold text-lg mb-1">Product Name</h4>
          <p class="text-sm text-gray-500">Short product description goes here.</p>
          <p class="mt-3 text-indigo-600 font-bold text-lg">$19.99</p>
          <button class="mt-4 w-full bg-indigo-600 text-white py-2 rounded-lg hover:bg-indigo-700 transition">Buy Now</button>
        </div>
      </div>
      <!-- Add more cards as needed -->
    </div>
  </section>

  <section id="about" class="bg-white py-20 px-4">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-bold text-indigo-600 mb-4">About Us</h3>
      <p class="text-lg text-gray-600">H.U Store is powered by Harry & Usman. We bring you an extensive range of high-quality products with fast, reliable delivery. We believe in trust, transparency, and customer satisfaction.</p>
    </div>
  </section>

  <section id="contact" class="bg-indigo-50 py-20 px-4">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-bold text-indigo-600 mb-4">Get in Touch</h3>
      <p class="text-lg text-gray-700">Have questions or want to place an order?</p>
      <p class="mt-2 text-indigo-700 font-semibold">📧 Email: <a href="mailto:hustore498@gmail.com" class="underline">hustore498@gmail.com</a></p>
      <p class="text-indigo-700 font-semibold">📱 Instagram: @hu_store_official</p>
    </div>
  </section>

  <footer class="bg-white border-t py-8 text-center text-sm text-gray-500">
    &copy; 2025 H.U Store | Powered by Harry & Usman. All rights reserved.
  </footer>
</body>
</html>
