<script setup lang="ts">
// 逻辑部分保持原样或留空即可
</script>

<template>
  <USeparator
    icon="i-simple-icons-nuxtdotjs"
    class="h-px"
  />

  <UFooter>
    <template #left>
      <p class="text-muted text-sm">
        Mirai.st • © {{ new Date().getFullYear() }}
      </p>
    </template>

    <template #right>
      <!-- 1. X (原 Twitter) -->
      <UButton
        to="https://x.com/oniyt1980"
        target="_blank"
        icon="i-simple-icons-x"
        aria-label="X (Twitter)"
        color="neutral"
        variant="ghost"
      />
      
      <!-- 2. Instagram -->
      <UButton
        to="https://www.instagram.com/miraist80/"
        target="_blank"
        icon="i-simple-icons-instagram"
        aria-label="Instagram"
        color="neutral"
        variant="ghost"
      />
      
    </template>
  </UFooter>
</template>