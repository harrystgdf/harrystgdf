<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>H.U Store | Online Shopping</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-800">
  <header class="bg-white shadow">
    <div class="max-w-7xl mx-auto px-4 py-6 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-indigo-600">H.U Store</h1>
      <nav>
        <ul class="flex gap-6 text-sm font-medium">
          <li><a href="#shop" class="hover:text-indigo-600">Shop</a></li>
          <li><a href="#about" class="hover:text-indigo-600">About</a></li>
          <li><a href="#contact" class="hover:text-indigo-600">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="text-center py-16 bg-gradient-to-r from-indigo-500 to-purple-500 text-white">
    <h2 class="text-4xl font-extrabold mb-4">Welcome to H.U Store</h2>
    <p class="text-lg">Your one-stop shop for all items – quality, speed & trust</p>
    <a href="#shop" class="mt-6 inline-block bg-white text-indigo-600 font-semibold px-6 py-3 rounded-full shadow hover:bg-gray-100 transition">Start Shopping</a>
  </section>

  <section id="shop" class="max-w-7xl mx-auto py-16 px-4">
    <h3 class="text-2xl font-bold mb-6 text-center">Featured Products</h3>
    <div class="grid md:grid-cols-3 gap-6">
      <!-- Example Product -->
      <div class="bg-white shadow rounded-lg p-4 text-center">
        <img src="https://via.placeholder.com/150" alt="Product" class="mx-auto mb-4">
        <h4 class="font-semibold text-lg">Product Name</h4>
        <p class="text-sm text-gray-600">Short description of the product.</p>
        <p class="mt-2 font-bold text-indigo-600">$19.99</p>
        <button class="mt-4 bg-indigo-600 text-white px-4 py-2 rounded hover:bg-indigo-700">Buy Now</button>
      </div>
      <!-- Add more product cards here -->
    </div>
  </section>

  <section id="about" class="bg-white py-16">
    <div class="max-w-4xl mx-auto px-4 text-center">
      <h3 class="text-2xl font-bold mb-4">About H.U Store</h3>
      <p class="text-gray-600">Powered by Harry & Usman, H.U Store is committed to delivering top-quality products with fast delivery and excellent customer support. We believe in building trust and long-term relationships with our customers.</p>
    </div>
  </section>

  <section id="contact" class="bg-gray-100 py-16">
    <div class="max-w-4xl mx-auto px-4 text-center">
      <h3 class="text-2xl font-bold mb-4">Contact Us</h3>
      <p>Email: <a href="mailto:hustore498@gmail.com" class="text-indigo-600">hustore498@gmail.com</a></p>
      <p>DM us on Instagram @hu_store_official 🛍️</p>
    </div>
  </section>

  <footer class="bg-white border-t mt-12 py-6 text-center text-sm text-gray-500">
    &copy; 2025 H.U Store. All rights reserved.
  </footer>
</body>
</html>
