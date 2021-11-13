<template>
  <div id="left">
    <input type="search" />
    <input type="submit" />
    <li v-for="entry in dict" :key="entry.id">
      {{ entry.value }}
    </li>
  </div>
  <div id="right"><textarea>翻译放这儿</textarea></div>
</template>

<script>
export default {
  data() {
    return {
      dict: [
      ],
    };
  },
};
</script>

<style>
</style>
