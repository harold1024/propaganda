<template>
  <div>
    <input class="search" type="text" placeholder="请输入关键字搜索该品牌主题" v-model="name" maxlength="6">
    <van-button type="primary">按钮</van-button>
  </div>
</template>

<script>

export default {
  data () {
    return {
      // name:'请输入关键字搜索该品牌主题',
    }
  },

  components: {
  },

  methods: {
  },

  created () {
    // let app = getApp()
  }
}
</script>

<style scoped>
.search{
  width: 80%;
  border: 1px solid #333;
  border-radius: 5px;
}

</style>
