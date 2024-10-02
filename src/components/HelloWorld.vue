<script>
export default {
  data(){
    return {
      name:"董佳"
    }
  },

  methods: {
    clickName(){
      this.name = '杨琴';
    }
  }
}
</script>

<template>
  <span>{{ name }}</span>
  <button @click="clickName"></button>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
