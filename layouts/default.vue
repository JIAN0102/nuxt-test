<!--
 * @Author:Jim Chen
 * @Date:2023-06-09 16:55:11
 * @LastEditors:Jim Chen
 * @LastEditTime:2023-06-09 16:59:47
 * @Description:
-->
<script setup lang="ts">
if (process.client) await navigateTo('/auth')
</script>

<template>
  <div>
    Setting Layout
    <slot />
  </div>
</template>