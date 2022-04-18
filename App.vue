<script>
export default {
 data () {
     return {
         count: 0
     }
 },
 methods: {
     incremet(){
         this.count++
     }
 }
}
</script>

<template>
    <button @click="increment">count is: {{ count }}</button>
</template>


