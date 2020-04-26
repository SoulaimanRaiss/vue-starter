<template>
  <div>
    <h1><span>You clicked {{count}} times</span></h1>
    <button @click="increment">Click Me!</button>
    
    
  </div>
</template>

<script>
export default {
  data() {
    return { count: 0 }
  },
  methods: {
    increment() {
      this.count += 1
    },
   
  }
}
</script>

