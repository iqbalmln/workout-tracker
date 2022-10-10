<template>
  <header class="bg-at-light-green text-white">
    <nav class="container py-5 px-4 flex sm:flex-row flex-col gap-4 items-center">
      <div class="flex items-center gap-x-4">
        <img src="../assets/images/dumbbell-light.png" alt="" class="w-14">
        <h1 class="text-lg">Active Tracker</h1>
      </div>
      <ul class="flex flex-1 justify-end gap-x-10">
        <router-link :to="{name: 'Home'}" class="cursor-pointer">Home</router-link>
        <router-link :to="{name: ''}" class="cursor-pointer">Create</router-link>
        <router-link :to="{name: 'Login'}" class="cursor-pointer">Login</router-link>
        <li class="cursor-pointer">Logout</li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  setup() {
    // Get user from store

    // Setup ref to router

    // Logout function

    return {};
  },
};
</script>
