<template>
  <div class="content">
    <Card/>
  </div>
</template>
<script>
  import Card from '@components/Card'
  export default {
    data() {
      return {
      }
    },
    components: {
      Card
    }
  }
</script>
<style>
  * {
    margin: 0;
    padding: 0;
  }
 .content {
   width: 100%;
   /* height: 100vh; */
   height: 1016px;
   display: flex;
   justify-content: center;
   background: url(../../assets/boot/background.jpg) no-repeat 0 0;
   background-size: 100% 100%;
 }
</style>