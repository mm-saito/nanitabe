<script setup lang="ts">
const { auth } = useSupabaseClient()
</script>
<template>
  <div class="card w-96 bg- bg-neutral text-primary">
  <div class="card-body">
    <h2 class="card-title">Login</h2>
    <div class="card-actions justify-end">
      <slot />
    </div>
  </div>
</div>
</template>