<script>
let id = 0
export default {
mounted (){
  this.$refs.p.textContent = 'mounted!'
}
}
</script>

<template>
<p ref="p">hello</p>
</template>
