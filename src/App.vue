<script setup>
import { ref } from 'vue';
const count = ref(0);
</script>
<template>
  <div style="min-height: 100vh; display: flex; align-items: center; justify-content: center; background: #0f172a; color: #f8fafc; font-family: system-ui, sans-serif; padding: 1rem;">
    <div style="max-width: 640px; width: 90%; background: #131b2e; border: 1px solid #1e293b; border-radius: 16px; padding: 2.5rem; text-align: center;">
      <div style="display: inline-block; padding: 0.25rem 0.75rem; border-radius: 999px; background: rgba(6,182,212,0.15); color: #06b6d4; font-size: 0.75rem; font-weight: bold; margin-bottom: 1rem;">[STANDALONE] Single-Page Application</div>
      <h1 style="font-size: 1.8rem; font-weight: 800; margin-bottom: 0.5rem; color: #42b883;">RapidFire Vue Application</h1>
      <p style="color: #94a3b8; font-size: 0.9rem; margin-bottom: 2rem;">Vue 3 Single-Page Application scaffolded cleanly with Vite.</p>
      <button style="padding: 0.75rem 1.5rem; border-radius: 8px; background: #42b883; color: #0f172a; border: none; font-weight: 600; cursor: pointer;" @click="count++">State Counter: {{ count }}</button>
    </div>
  </div>
</template>
