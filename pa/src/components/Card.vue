<template>
  <div class="card-content">

  </div>
</template>
<script>
  export default {
    data() {
      return {
      }
    },
    props: {
      title: {
        type: String,
        required: true
      },
      mode: {
        type: String,
        required: true
      },
      num: {
        type: Object,
        required: true,
        default: function() {
          return {
            red: 6,
            blue: 1
          }
        }
      },
      moneyPool: {
        type: Number,
        required: true
      }
    }
  }
</script>
<style scoped>
  .card-content{
    width: 600px;
    height: 360px;
    border: 1px solid #EEEEEE;
    border-radius: 20px;
  }
</style>
