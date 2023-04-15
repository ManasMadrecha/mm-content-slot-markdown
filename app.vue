<template>
  <div>
    <MarkdownContent>{{ text }}</MarkdownContent>
    <MarkdownContent>**app**</MarkdownContent>
    <NuxtPage />
  </div>
</template>

<script lang="ts" type="setup">
const text = `## I am H2`;
</script>
