<template>
  <div class="page">
    <h2 class="header">Generator</h2>
    <div class="intro">
      <p>代码生成器，可以通过界面配置快速生成包括 entity、mapper、xml、service、controller 以及页面的相关代码的前端页面</p>
      <p>项目地址：<a href="https://github.com/shitongtong/generator-front.git">
      https://github.com/shitongtong/generator-front.git</a>
        , 项目使用指南如下图，具体环境搭建参考安装教程。
      </p>
    </div>
    <div>
      <div class="title">使用指南</div>
      <div class="step">
        <span>1.配置数据源</span>
      </div>
      <div  class="image">
        <img src="https://images.gitee.com/uploads/images/2018/1114/180145_1b395632_645970.png" />
      </div>
    </div>
    <div>
      <div class="step">
        <span>2.选择数据库表</span>
      </div>
      <div class="image">
        <img src="https://images.gitee.com/uploads/images/2018/1114/180317_ca91ceb2_645970.png" />
      </div>
    </div>
    <div>
      <div class="step">
        <span>3.编辑信息，生成代码</span>
      </div>
      <div  class="image">
        <img src="https://images.gitee.com/uploads/images/2018/1114/180642_2c4f986d_645970.png" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Intro'
}
</script>

<style>
.header {
  font-size: 28px;
  text-align: left;
  padding: 10px;
}
.intro {
  font-size: 18px;
  text-align: left;
  padding-left: 10px;
}
.title {
  font-size: 30px;
  text-align: left;
  padding: 10px;
}
.step {
  font-size: 18px;
  text-align: left;
  padding: 10px;
}
.image {
  text-align: left;
  padding: 10px;
}
img {
  
  width: 1000px;
  height: 500px;
}
</style>
