<template>
  <div class="p-8 bg-gray-50 min-h-screen">
    <!-- Cart Header -->
    <div class="flex justify-between items-center mb-6">
      <div class="flex items-center">
        <div class="flex items-center bg-red-100 rounded-full p-3">
          <i class="text-red-500 fas fa-shopping-cart"></i>
        </div>
        <div class="ml-4">
          <h2 class="text-xl font-semibold">Item Cart</h2>
          <p class="text-sm text-gray-500">Product Summary</p>
        </div>
      </div>
      <div class="flex space-x-8">
        <div class="flex items-center gap-2">
          <i class="fa-solid fa-file-invoice"></i>
          <div>
            <h2 class="text-xl font-semibold">Billing</h2>
            <p class="text-sm text-gray-500">Billing Information</p>
          </div>
        </div>
        <div class="flex items-center gap-2">
          <i class="fa-regular fa-credit-card"></i>
          <div>
            <h2 class="text-xl font-semibold">Payment</h2>
            <p class="text-sm text-gray-500">Add & Update Card</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Cart Items Table -->
    <div class="bg-white shadow rounded-lg p-6">
      <div class="overflow-x-auto">
        <table class="min-w-full text-left">
          <thead>
            <tr class="border-b">
              <th class="py-3">Product</th>
              <th class="py-3">Price</th>
              <th class="py-3">Quantity</th>
              <th class="py-3">Total</th>
              <th class="py-3"></th>
            </tr>
          </thead>
          <tbody>
            <tr class="border-b">
              <td class="py-4 flex items-center space-x-4">
                <img
                  src="https://via.placeholder.com/50"
                  alt="Teddybear"
                  class="w-16 h-16 object-cover rounded"
                />
                <div>
                  <h3 class="font-medium">Cute Soft Teddybear</h3>
                  <p class="text-sm text-gray-500">Size: 8 | Color: Dark Red</p>
                </div>
              </td>
              <td class="py-4">
                <div class="text-gray-400 line-through">$175</div>
                <div class="font-semibold">$200</div>
              </td>
              <td class="py-4">
                <div class="flex items-center border rounded-lg w-max">
                  <button class="px-3 py-2 text-gray-500">-</button>
                  <input
                    type="text"
                    value="1"
                    class="w-12 text-center focus:outline-none"
                  />
                  <button class="px-3 py-2 text-gray-500">+</button>
                </div>
              </td>
              <td class="py-4 font-semibold">$200</td>
              <td class="py-4">
                <button class="text-red-500">
                  <i class="fas fa-trash"></i>
                </button>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>

    <!-- Order Summary -->
    <div class="bg-white shadow rounded-lg p-6 mt-8">
      <h2 class="text-lg font-semibold mb-6">Order Summary</h2>
      <div class="space-y-4">
        <div class="flex justify-between">
          <span>Sub Total</span>
          <span>$200</span>
        </div>
        <div class="flex justify-between">
          <span>Discount 5%</span>
          <span class="text-red-500">- $10</span>
        </div>
        <div class="flex justify-between">
          <span>Shipping Charges</span>
          <span>-</span>
        </div>
        <div class="flex justify-between font-semibold text-lg">
          <span>Total</span>
          <span>$190</span>
        </div>
      </div>
    </div>

    <!-- Buttons -->
    <div class="flex justify-between items-center mt-8">
      <button class="px-6 py-2 text-pink-500 bg-pink-100 rounded-lg">
        Continue Shopping
      </button>
      <button class="px-6 py-2 text-white bg-orange-500 rounded-lg">
        Checkout
      </button>
    </div>
  </div>
</template>

<script></script>

<style></style>
