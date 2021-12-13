<template>
  <div>
    <Menubar>
      <template #start> Before </template>
      <template #item="{ item }">
        <a :href="item.url">{{ item.label }}</a>
      </template>
    </Menubar>
  </div>
</template>

<script lang="ts"></script>
