<!-- Please remove this file from your project -->
<template>
<div class="min-h-screen flex">
<NavLeft />
  <div class="bg-indigo-50  py-12 px-10 w-5/6">
    <div class="flex justify-between">
      <div>
        <h4 class="text-sm font-bold text-indigo-600">Hi Andrei,</h4>
        <h1 class="text-4xl font-bold text-indigo-900 mt-">Your Dive Log!</h1>
      </div>
      <div>
        <div class="flex items-center border rounded-lg bg-white w-max py-2 px-4 space-x-3">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
          </svg>
          <input type="text" placeholder="Search" />
        </div>
      </div>
    </div>
<div class="grid grid-cols-4 gap-3 py-5">
  <DiveCard /><DiveCard /><DiveCard /><DiveCard /><DiveCard /><DiveCard /><DiveCard /><DiveCard />

</div>


    </div>

  </div>
</div>


