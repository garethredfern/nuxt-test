<template>
  <div>
    <header class="p-5">
      Logo
    </header>
    <main>
      <slot />
    </main>
  </div>
</template>

<script lang="ts" setup>
useMeta({
  meta: [
        { name: 'viewport', content: 'width=device-width, initial-scale=1, maximum-scale=1' }
      ],
      bodyAttrs: {
        class: 'bg-gray-200'
      }
});
</script>
