<template>
    <div class="zh-container">
      <h1>Hello, Zh!</h1>
      <p>This is a simple Vue component.</p>
    </div>
  </template>
  
  <script>
  export default {
    name: 'ZhComponent',
    data() {
      return {
        // 可以在这里定义组件的数据
      };
    },
    methods: {
      // 可以在这里定义组件的方法
    }
  };
  </script>
  
  <style scoped>
  .zh-container {
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 4px;
    margin: 20px;
  }
  </style>