<template>
  <!-- components/TopMenu.vue -->
  <div class="menupage">
    <el-menu :default-active="activeIndex2" class="el-menu-demo" mode="horizontal" @select="handleSelect"
      background-color="#545c64" text-color="#fff" active-text-color="#ffd04b">
      <p class="logo-title"><i class="el-icon-user"></i>Coderuan</p>
      <el-menu-item index="1" style="margin-left:250px;">首页</el-menu-item>
      <el-menu-item index="2">个人简介</el-menu-item>
      <el-menu-item index="3">爱好</el-menu-item>
      <el-menu-item index="4">项目经历</el-menu-item>
      <el-menu-item index="5">技能</el-menu-item>
    </el-menu>
  </div>
</template>
<style>
  .menupage {
    position: fixed;
    width: 100%;
    top: 0px;
    z-index: 100;
  }

  .menupage .el-menu.el-menu--horizontal {
    border-bottom: none;
    height: 60px;
    line-height: 60px;
  }

  .menupage .el-menu.el-menu--horizontal>.el-menu-item,
  .menupage .el-menu--horizontal>.el-submenu .el-submenu__title {
    height: 60px;
    line-height: 60px;
    padding: 0px 20px;
    font-size: 10px;
    letter-spacing: 4px;
  }

  .menupage .el-menu--horizontal>.el-menu-item.is-active,
  .menupage .el-menu--horizontal>.el-submenu.is-active .el-submenu__title {
    border-bottom-width: 4px;
  }

  .menupage .logo-title .el-icon-user {
    margin-right: 5px;
  }
</style>
<style scoped>
  .logo-title {
    position: absolute;
    left: 100px;
    top: 0px;
    color: #fff;
    font-size: 26px;
    cursor: pointer;
  }

  .logo-title img {
    width: 80px;
    outline: none;
    vertical-align: middle;
  }
</style>
<script>
  export default {
    name: 'topMenu',
    data() {
      return {
        activeIndex2: '1'
      }
    },
    methods: {
      handleSelect(key, keyPath) {
        var name = ''
        if (key === '1') {
          name = 'root'
          var targetEle = document.querySelector('.' + name)
          var offsetTop = targetEle.offsetTop
          document.documentElement.scrollTop = offsetTop-60
        }

        if (key === '2') {
          name = 'title'
          var targetEle = document.querySelector('.' + name)
          var offsetTop = targetEle.offsetTop
          document.documentElement.scrollTop = offsetTop + 750
        }

        if (key === '3') {
          name = 'content-love'
          var targetEle = document.querySelector('.' + name)
          var offsetTop = targetEle.offsetTop
          document.documentElement.scrollTop = offsetTop + 810
        }

        if (key === '4') {
          name = 'content-left'
          var targetEle = document.querySelector('.' + name)
          var offsetTop = targetEle.offsetTop
          document.documentElement.scrollTop = offsetTop + 820
        }

        if (key === '5') {
          name = 'content-right'
          var targetEle = document.querySelector('.' + name)
          var offsetTop = targetEle.offsetTop
          document.documentElement.scrollTop = offsetTop + 1900
        }



        // if (key === '4') name = 'content-left'
        // if (key === '3') name = 'securityresearch'
        // if (key === '2') name = 'aboutus'
        // if (key === '5') name = 'content-right'


      }
    }
  }
</script>
