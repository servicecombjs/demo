<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      一个分享技术的博客空间
    </p>
    <h3>关注技术</h3>
    <ul>
      <li>Java</li>
      <li>babel</li>
      <li>typescript</li>
      <li>pwa</li>
    </ul>
    <ul>
      <li><a href="http://beian.miitbeian.gov.cn" target="_blank" rel="noopener">沪ICP备19039564</a></li>
    </ul>
    
    <!-- <el-button type="text">文字按钮</el-button>
    <el-button type="primary" :loading="true">加载中</el-button> -->
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class HelloWorld extends Vue {
  @Prop() private msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus">
h3
  margin 40px 0 0

ul
  list-style-type none
  padding 0

li
  display inline-block
  margin 0 10px

a
  color #42b983
</style>
