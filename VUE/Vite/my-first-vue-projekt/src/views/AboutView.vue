<script setup>
  import {useFlash} from "../composables/useFlash";
  let { flash } = useFlash();
</script>

<template>
  <div class="about">
    <p>
      <button @click="flash('It Works On The About Page!')">Click Me</button>
    </p>
  </div>
</template>
