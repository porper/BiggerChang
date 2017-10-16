<template>
  <div id="app">
    <header class="am-g am-g-fixed blog-fixed blog-text-center blog-header">
      <div class="am-u-sm-8 am-u-sm-centered">
          <img width="200" src="http://s.amazeui.org/media/i/brand/amazeui-b.png" alt="Amaze UI Logo"/>
          <h2 class="am-hide-sm-only">中国首个开源 HTML5 跨屏前端框架</h2>
      </div>
    </header>
    <hr>
    <!-- nav start -->
    <nav class="am-g am-g-fixed blog-fixed blog-nav">
        <button class="am-topbar-btn am-topbar-toggle am-btn am-btn-sm am-btn-success am-show-sm-only blog-button" data-am-collapse="{target: '#blog-collapse'}"><span class="am-sr-only">导航切换</span> <span class="am-icon-bars"></span></button>

        <div class="am-collapse am-topbar-collapse" id="blog-collapse">
            <ul class="am-nav am-nav-pills am-topbar-nav">
                <li class="am-active"><a href="javascript:void(0)">首页</a></li>


                <li><a href="javascript:void(0)">学习笔记</a></li>
                <li><a href="javascript:void(0)">自制项目</a></li>
                <li><a href="javascript:void(0)">生活点滴</a></li>
                <li><a href="javascript:void(0)">关于本站</a></li>
            </ul>
            <form class="am-topbar-form am-topbar-right am-form-inline" role="search">
                <div class="am-form-group">
                    <input type="text" class="am-form-field am-input-sm" placeholder="搜索">
                </div>
            </form>
        </div>
    </nav>
    <hr>
    <!-- nav end -->
      <!-- banner start -->
    <div class="am-g am-g-fixed blog-fixed am-u-sm-centered blog-article-margin">
        <div data-am-widget="slider" class="am-slider am-slider-b1" data-am-slider='{&quot;controlNav&quot;:false}'>
            <ul class="am-slides">
                <li>
                    <img src="/static/i/b1.jpg">
                </li>
                <li>
                    <img src="/static/i/b2.jpg">
                </li>
                <li>
                    <img src="/static/i/b3.jpg">
                </li>
                <li>
                    <img src="/static/i/b2.jpg">
                </li>
            </ul>
        </div>
    </div>
    <!-- banner end -->

    <!-- content start -->
    <router-view></router-view>
    <!-- content end -->

    <!-- footer start -->
    <footer class="blog-footer">
        <div class="am-g am-g-fixed blog-fixed am-u-sm-centered blog-footer-padding">
            <div class="am-u-sm-12 am-u-md-4- am-u-lg-4">
                <h3>模板简介</h3>
                <p class="am-text-sm">这是一个使用amazeUI做的简单的前端模板。<br> 博客/ 资讯类 前端模板 <br> 支持响应式，多种布局，包括主页、文章页、媒体页、分类页等<br>嗯嗯嗯，不知道说啥了。外面的世界真精彩<br><br> Amaze UI 使用 MIT 许可证发布，用户可以自由使用、复制、修改、合并、出版发行、散布、再授权及贩售 Amaze UI 及其副本。</p>
            </div>
            <div class="am-u-sm-12 am-u-md-4- am-u-lg-4">
                <h3>社交账号</h3>
                <p>
                    <a href=""><span class="am-icon-qq am-icon-fw am-primary blog-icon blog-icon"></span></a>
                    <a href=""><span class="am-icon-github am-icon-fw blog-icon blog-icon"></span></a>
                    <a href=""><span class="am-icon-weibo am-icon-fw blog-icon blog-icon"></span></a>
                    <a href=""><span class="am-icon-reddit am-icon-fw blog-icon blog-icon"></span></a>
                    <a href=""><span class="am-icon-weixin am-icon-fw blog-icon blog-icon"></span></a>
                </p>
                <h3>Credits</h3>
                <p>我们追求卓越，然时间、经验、能力有限。Amaze UI 有很多不足的地方，希望大家包容、不吝赐教，给我们提意见、建议。感谢你们！</p>
            </div>
            <div class="am-u-sm-12 am-u-md-4- am-u-lg-4">
                <h1>我们站在巨人的肩膀上</h1>
                <h3>Heroes</h3>
                <p>
                    <ul>
                        <li>jQuery</li>
                        <li>Zepto.js</li>
                        <li>Seajs</li>
                        <li>LESS</li>
                        <li>...</li>
                    </ul>
                </p>
            </div>
        </div>
        <div class="blog-text-center">© 2015 AllMobilize, Inc. Licensed under MIT license. Made with love By LWXYFER. 模板收集自 <a href="http://www.cssmoban.com/" target="_blank" title="模板之家">模板之家</a> - More Templates <a href="http://www.cssmoban.com/" title="网页模板" target="_blank">网页模板</a></div>
    </footer>

    <!-- footer end -->

  </div>
</template>

<script>

export default {
  name: 'app',
}
</script>

<style>

</style>
