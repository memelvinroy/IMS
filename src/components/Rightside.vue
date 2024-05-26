<template>
    <main>
        <div class="bg-gray-300 p-2  h-11 flex items-center">
            <div class="flex items-center justify-center gap-7">
                <i class="fa-solid fa-bars"></i>
                <h2 class="text-lg font-semibold">Inventory Management</h2>
            </div>
            <div class=" ml-auto flex items-center ">
                <i class="fa-regular fa-bell"></i>
                <img src="../assets/Group 14.svg" alt="" class="ml-4">
                <h3 class="p-3">kristin samuel</h3>
                <i class="fa-solid fa-caret-down"></i>
               </div>
              </div>
              <div class="bg-gray-100 p-2  h-11 flex items-center rounded mx-4 mt-4">
                <ul class="flex items-center gap-x-8 p-6 ">
                    <li>Inventory</li>
                    <li>Equipment Type </li>
                    <li>Vendor</li>
                    <li>Location</li>
                </ul>
              </div>
              <div class="bg-gray-100 p-2  h-16 flex items-center rounded mx-4 mt-4">
                <input type="text" placeholder="Search by inventory name" class="w-96 h-10 px-3 border-transparent focus:outline-none rounded border-opacity-25 bg-opacity-25"><i class="fa-solid fa-magnifying-glass p-3"></i>
                <button class="bg-black text-white rounded px-4 py-2 ml-auto mr-4 flex items-center">
<i class="fa-solid fa-plus mr-2"></i> Add Inventory</button>

              </div>
    </main>
</template>
