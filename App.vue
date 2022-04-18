<script>
export default {
   data() {
       return {
          titleClass: 'title'
       }
   }
}
</script>

<template>
   <h1 :class="titleClass">Make me blue</h1>
</template>

<style scoped>
.title{
    color:blue;
}
</style>
