<template>
  <div class="rounded-b-[24px] overflow-hidden">
    <svg
      width="393"
      height="95"
      viewBox="0 0 393 95"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <path
        d="M90.5 21.3015C60 4.80148 29 -26.1985 -26 48.3015L-49 123.801H396.5L432 96.8008C429 80.6343 413.8 42.9015 377 21.3015C331 -5.69852 267 3.30078 209.5 35.3008C152 67.3008 121 37.8015 90.5 21.3015Z"
        :fill="curveFill"
      />
    </svg>
  </div>
</template>

<script setup lang="ts">
defineProps({
    curveFill: {
        type: String,
        default: '#fff'
    }
})
</script>

<style></style>
