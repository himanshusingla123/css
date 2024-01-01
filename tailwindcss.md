1. **Button**: To create a button with tailwind CSS, you can use the following code:
 ```tailwindcss
 <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
  Button
 </button>
 ```
2. **Card**: To create a card component with tailwind CSS, you can use the following code:
  ```card
  <div class="max-w-sm rounded overflow-hidden shadow-lg">
  <img class="w-full" src="https://source.unsplash.com/random" alt="Random image">
  <div class="px-6 py-4">
     <div class="font-bold text-xl mb-2">Card title</div>
     <p class="text-gray-700 text-base">
       This is a sample card component using tailwind CSS.
     </p>
  </div>
  <div class="px-6 py-4">
     <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2">#photography</span>
     <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2">#travel</span>
     <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700">#wanderlust</span>
  </div>
 </div>
 ```
3. **Form**: To create a form component with tailwind CSS, you can use the following code:
  ```form
 <form class="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4">
  <div class="mb-4">
     <label class="block text-gray-700 text-sm font-bold mb-2" for="username">
       Username
     </label>
     <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="username" type="text" placeholder="Username">
  </div>
  <div class="mb-6">
     <label class="block text-gray-700 text-sm font-bold mb-2" for="password">
       Password
     </label>
     <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 mb-3 leading-tight focus:outline-none focus:shadow-outline" id="password" type="password" placeholder="******************">
  </div>
  <div class="flex items-center justify-between">
     <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline" type="submit">
       Sign In
     </button>
  </div>
 </form>
  ```
4. **Navigation Bar**: To create a navigation bar with tailwind CSS, you can use the following code:
   ```navbar
   <nav class="bg-gray-800">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex items-center justify-between h-16">
        <div class="flex items-center">
          <div class="hidden md:block">
            <div class="ml-10 flex items-baseline space-x-4">
              <a href="#" class="text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Home</a>
              <a href="#" class="text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium">About</a>
              <a href="#" class="text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Contact</a>
            </div>
         </div>
      </div>
     </div>
   </div>
  </nav>
  
 ```
