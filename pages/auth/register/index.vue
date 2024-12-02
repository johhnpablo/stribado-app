<template>
  <div class="flex items-center justify-center min-h-screen bg-slate-900">
    <div class="bg-slate-800 w-3/12 p-6 rounded-lg h-min-60 shadow-sm">
      <div class="flex items-center justify-center w-full mb-4">
        <h2 class="font-sans text-2xl font-medium">Stribado Wallet 💰</h2>
      </div>
      <form-register />
    </div>
  </div>
</template>

<script lang="ts" setup>
import formRegister from "../-components/form-register.vue";

</script>