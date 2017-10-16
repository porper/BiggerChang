<template>
<div class="am-g am-g-fixed blog-fixed" id="content">
  <text-list></text-list>
  <div class="am-u-md-4 am-u-sm-12 blog-sidebar">
    <about-me></about-me>
    <content-me></content-me>
    <tag-cloud></tag-cloud>
    <category></category>
  </div>
</div>
</template>
<script>
import textList from './textList/textList'
import aboutMe from './aboutMe/aboutMe'
import contentMe from './contentMe/contentMe'
import tagCloud from './tagCloud/tagCloud'
import category from './category/category'
export default {
  name: "content",
  data () {
    return {
    }
  },
  components: {
    textList,aboutMe,contentMe,tagCloud,category
  }
}
</script>
<style lang="css" rel="stylesheet/css" scoped>
</style>