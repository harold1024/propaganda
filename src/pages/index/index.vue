<template>
  <div>
    <!-- <input class="search" type="text" placeholder="请输入关键字搜索该品牌主题" v-model="name" maxlength="6">
    <van-button type="primary">按钮</van-button>
    <van-cell-group>
    <van-field
      :value="value"
      placeholder="请输入用户名"
      :border="false"
      bind:change="onChange"
    />
    </van-cell-group> -->
    <van-search placeholder="请输入搜索关键词" :value="value1" background="#4fc08d"/>
  </div>
</template>

<script>

export default {
  data () {
    return {
      // name:'请输入关键字搜索该品牌主题',
      value: '',
      value1: ''
    }
  },

  components: {
  },

  methods: {
    onChange(event) {
      // event.detail 为当前输入的值
      console.log(event.detail);
    }
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
