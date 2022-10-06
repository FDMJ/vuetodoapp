<template>
  <div>
    <h1>{{message.toLowerCase()}}</h1>
    <h1>{{count}}</h1>
    <button @click="countUp">Hochzählen</button>
  </div>
</template>

<script>
export default {
  name: 'Todo',
  data(){
    return {
      message: "Hello World",
      count: 0,
    }
  },
  methods: {
    countUp(){
      this.count++;
    }
  }
}
</script>
