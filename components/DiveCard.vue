<template>

  <div class="max-w-md bg-white rounded-xl overflow-hidden cursor-pointer shadow-lg hover:shadow-2xl hover:scale-105 transform transition-all duration-500">
    <div class="p-3 relative">
      <div class="grid grid-cols-3 gap-3 absolute right-0 p-3 mr-3 bg-gray-900 rounded-bl-xl  rounded-tr-xl  opacity-50">
        <div class="flex items-center">
          <span>
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a1.994 1.994 0 01-1.414-.586m0 0L11 14h4a2 2 0 002-2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2v4l.586-.586z" />
            </svg>
          </span>
          <span class="text-white text-xs pl-1">45ft</span>
        </div>
         <div class="flex items-center">
          <span>
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a1.994 1.994 0 01-1.414-.586m0 0L11 14h4a2 2 0 002-2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2v4l.586-.586z" />
            </svg>
          </span>
          <span class="text-white text-xs pl-1">45min</span>
        </div>

    <div class="flex items-center">
          <span>
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a1.994 1.994 0 01-1.414-.586m0 0L11 14h4a2 2 0 002-2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2v4l.586-.586z" />
            </svg>
          </span>
          <span class="text-white text-xs pl-1">#:0001</span>
        </div>
     </div>
      <img class="rounded-xl" src="../static/bg-diving.jpg" alt="Diver" />
    </div>

      <div class=" grid grid-cols-1 gap-1 px-3">
  <div class="py-1 w-4/6 font-bold">Diving the Mollasses Reef</div>

    </div>
  <div class=" grid grid-cols-2 gap-1 p-3">

  <div class="w-1/6 text-xs">02/19/2020</div>
  <div class="w-5/6 text-xs">Key Largo, Florida</div>
    </div>
  </div>


</template>
<style scoped>
.bg-card-image {
  background-image: url('./static/bg-card.png');
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
