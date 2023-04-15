<template>
  <div>
    <MarkdownContent class="">{{ text }}</MarkdownContent> text
    <MarkdownContent class="">## hello</MarkdownContent> text
    <NuxtPage />
  </div>
</template>

<script lang="ts" type="setup">
const text = `## I am H2`;
</script>
