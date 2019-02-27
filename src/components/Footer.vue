<template>
  <footer>
    <p>{{title}}</p>
  </footer>
</template>

<script>
    export default {
        name: "app-footer",
      data(){
          return{
   title:'hellow word'
          }
      },
    }
</script>

<style scoped>
footer{
  background: #222;
  padding: 6px;
}
  p {
    color: lightgreen;
    text-align: center;
  }
</style>
