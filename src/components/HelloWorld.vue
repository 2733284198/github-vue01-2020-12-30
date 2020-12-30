<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h1>{{ site }}</h1>
    <h1>{{ details() }}</h1>
  </div>
</template>

<script>

export default {
  name: 'hello',
  data () {
    return {
      msg: '欢迎来到菜鸟教程！',
      site: 'site01'
    }
  },

  methods:{
    details:function () {
      return  this.site + " - 学的不仅是技术，更是梦想！";
    }
  }

}


</script>
