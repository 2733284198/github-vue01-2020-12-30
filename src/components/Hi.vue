<template>
  <div class="hi">
    <h1> {{ value1 }} </h1>
  </div>
</template>

<script>
export default {
  name: "Hi",
  data() {
    return {
      value1 : 'hi-value1'
    }
  },

  methods:{
    click1:function () {
      this.value1 = "hi-value1 点击了"
    }
  }
}
</script>

<style scoped>

</style>
