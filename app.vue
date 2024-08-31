<template>
  <div class="  p-2 h-screen bg-blue-600 ">
    <div class=" h-full  grid grid-cols-2 " >
      <!--  t  -->
      <div class="border-l-4  bg-blue-600 border-t-4 border-black"
           >
        <div class=" flex items-center justify-center   h-full " >
          <h1 class="text-9xl">T</h1>
        </div>
      </div>
      <!--  e  -->
      <div class=" border-t-4 border-black  " >
        <div class="bg-white flex items-center  justify-center  text-9xl  border-r-4 border-blue-600 h-full"
             style="box-shadow: inset 0 -4px 4px -2px rgba(0, 0, 0, 0.5);">
          <h1 class="text-9xl text-gray-700" >E</h1>
        </div>
      </div>
      <!--  s  -->
      <div class="border-b-4 border-black   " >
        <div class="flex  bg-white items-center justify-center text-9xl border-l-4 border-blue-600 h-full"
             style="box-shadow: inset 0 4px 4px -2px rgba(0, 0, 0, 0.5);"
        >
          <h1 class="text-9xl text-gray-700">S</h1>
        </div>
      </div>
      <!--  t  -->
      <div class=" border-b-4  border-black  ">
        <div class="bg-blue-600 flex items-center justify-center   text-9xl border-black border-r-4 h-full">
          <h1 class="text-9xl">T</h1>
        </div>
      </div>
    </div>
  </div>

</template>
<script setup lang="ts">
</script>
<style scoped>
.shadow-example {
  border-l-4: 4px solid;
  border-t-4: 4px solid;
  border-color: black;
  background-color: blue;
  padding: 20px; /* Add padding to ensure the content doesn't touch the borders */

  /* Box shadow with vendor prefixes for compatibility */
  -webkit-box-shadow: 0px 8px 5px 0px rgba(0, 0, 0, 0.75); /* For older WebKit browsers */
  -moz-box-shadow: 0px 8px 5px 0px rgba(0, 0, 0, 0.75);    /* For older Mozilla browsers */
  box-shadow: 0px 8px 5px 0px rgba(0, 0, 0, 0.75);          /* Standard syntax */
}

.content {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}
</style>