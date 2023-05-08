<template>
  <div class="bg-black bg-opacity-20 rounded-3xl overflow-hidden">
    <div class="header">
      <div class="h-32 w-full flex">
        <img src="https://via.placeholder.com/800x600" class=" w-full h-full object-cover">
      </div>
    </div>
    
    <div class="body relative p-5">
      <avatar class="w-12 h-12 absolute rounded-full right-2 -top-5 overflow-hidden"/>
      <h5 class="text-xs opacity-50 mb-2">
        Andy William 
        <div class="w-2 h-2 inline-block ml-2 rounded-full bg-green-400"></div>
      </h5>
      <h4>Basic how to ride your skateboard comfortly</h4>
      <span class="text-xs flex items-center space-x-3 opacity-50 mt-3">
        <span>53k views</span>
        <div class="w-1 h-1 rounded-full bg-gray-300"></div>
        <span>2 weeks ago</span>
      </span>
    </div>
  </div>
</template>

<script>
import Avatar from './Avatar.vue'
export default {
  components: {
    Avatar
  }
}
</script>

<style>

</style>