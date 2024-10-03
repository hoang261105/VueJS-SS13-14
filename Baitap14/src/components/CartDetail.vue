<template>
  <div class="container mx-auto p-8">
    <!-- Product Details Section -->
    <div class="flex space-x-8">
      <!-- Left Column: Image Carousel -->
      <div class="w-2/3">
        <div class="relative">
          <img
            src="https://hoahongsi.com/Upload/cate/dauco4-3673.jpg"
            alt="Product Image"
            class="rounded-lg shadow-md"
          />
          <!-- Image carousel buttons -->
          <button
            class="absolute left-2 top-1/2 transform -translate-y-1/2 bg-gray-100 text-gray-700 p-2 rounded-full shadow-md"
          >
            ‹
          </button>
          <button
            class="absolute right-2 top-1/2 transform -translate-y-1/2 bg-gray-100 text-gray-700 p-2 rounded-full shadow-md"
          >
            ›
          </button>
        </div>

        <!-- Thumbnail Images -->
        <div class="flex space-x-4 mt-4">
          <img
            src="https://hoanghamobile.com/tin-tuc/wp-content/uploads/2023/06/Sach-hay.jpg"
            class="w-20 h-20 object-cover rounded-lg cursor-pointer"
          />
          <img
            src="https://bizweb.dktcdn.net/100/340/129/products/tai-nghe-sony-ch-ch520-cuongphanvn-13.jpg?v=1680431911657"
            class="w-20 h-20 object-cover rounded-lg cursor-pointer"
          />
          <img
            src="https://via.placeholder.com/80"
            class="w-20 h-20 object-cover rounded-lg cursor-pointer"
          />
          <img
            src="https://via.placeholder.com/80"
            class="w-20 h-20 object-cover rounded-lg cursor-pointer"
          />
          <img
            src="https://via.placeholder.com/80"
            class="w-20 h-20 object-cover rounded-lg cursor-pointer"
          />
        </div>
      </div>

      <!-- Right Column: Product Info -->
      <div class="w-1/3">
        <!-- In Stock Tag -->
        <div class="flex items-center space-x-2 mb-2">
          <span
            class="bg-green-100 text-green-600 text-xs font-semibold px-2 py-1 rounded"
            >In Stock</span
          >
          <span class="text-gray-400 text-xs">kids</span>
        </div>

        <!-- Product Title -->
        <h1 class="text-2xl font-semibold">Cute Soft Teddybear</h1>
        <p class="text-gray-500 text-sm mt-2">
          Vuhogi tullofi ruzhiru zevwopaz pi kamim vibrucvil vebbeji pomidwi...
        </p>

        <!-- Price & Rating -->
        <div class="mt-4">
          <div class="flex items-center space-x-4">
            <span class="text-2xl font-semibold text-red-500">$200</span>
            <span class="text-gray-400 line-through">$175</span>
          </div>
          <div class="flex items-center space-x-1 mt-2">
            <div class="text-yellow-400">
              <i class="fas fa-star"></i><i class="fas fa-star"></i
              ><i class="fas fa-star"></i><i class="fas fa-star"></i
              ><i class="fas fa-star-half-alt"></i>
            </div>
            <span class="text-sm text-gray-500">(236 reviews)</span>
          </div>
        </div>

        <!-- Color Selection -->
        <div class="mt-6">
          <h3 class="font-semibold mb-2">Colors</h3>
          <div class="flex space-x-3">
            <button
              class="w-8 h-8 bg-orange-400 rounded-full border-2 border-transparent focus:ring-2 focus:ring-orange-500"
            ></button>
            <button
              class="w-8 h-8 bg-yellow-400 rounded-full border-2 border-transparent focus:ring-2 focus:ring-yellow-500"
            ></button>
            <button
              class="w-8 h-8 bg-teal-400 rounded-full border-2 border-transparent focus:ring-2 focus:ring-teal-500"
            ></button>
            <button
              class="w-8 h-8 bg-pink-400 rounded-full border-2 border-transparent focus:ring-2 focus:ring-pink-500"
            ></button>
          </div>
        </div>

        <!-- Quantity -->
        <div class="mt-6">
          <h3 class="font-semibold mb-2">Quantity</h3>
          <div class="flex items-center border rounded-lg">
            <button class="px-3 py-2 text-gray-500">-</button>
            <input
              type="text"
              value="1"
              class="w-12 text-center focus:outline-none"
            />
            <button class="px-3 py-2 text-gray-500">+</button>
          </div>
        </div>

        <!-- Buttons -->
        <div class="mt-8 space-y-4">
          <button class="w-full bg-orange-500 text-white py-3 rounded-lg">
            Buy Now
          </button>
          <button class="w-full bg-teal-500 text-white py-3 rounded-lg">
            Add to Cart
          </button>
        </div>

        <!-- Shipping & Dispatch -->
        <div class="mt-4">
          <p class="text-gray-500">Dispatched in 2-3 weeks</p>
          <a href="#" class="text-blue-500 text-sm"
            >Why the longer time for delivery?</a
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style></style>
