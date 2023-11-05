<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <h1>Inertia Theory</h1>

  <div class="card">
    <p>
      <code>Theory part inside "Readme.md" file</code>
    </p>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
