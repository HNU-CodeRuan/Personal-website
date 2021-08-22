<template>
  <div class="root">
    <swiper id="swiperBox" v-bind:options="swiperOption" ref="mySwiper">
      <swiper-slide class="swiper-slide">
        <div class="page1">
          <div class="wrap">
            <div class="main">
              <h1 class="main-title">Hi, I'm coderuan</h1>
              <p>你好，我叫阮成春</p>
              <p>很高兴能在茫茫人海中遇到你</p>
              <p>来都来了</p>
              <p>不如...</p>
              <p>来互相认识一下吧？</p>
            </div>
          </div>
        </div>
      </swiper-slide>

      <div class="swiper-pagination" slot="pagination"></div>
    </swiper>
  </div>
</template>

<script>
  export default {
    name: 'Aboutus',
    data() {
      return {}
    },
    mounted() {},
    computed: {},
  }
</script>

<style lang='less' scoped>
  
  .root{
    margin-top: 60px;
    height: 887px;
  }
  #swiperBox {
    min-width: 1420px;
  }

  .fadeIn {
    animation: fadeInUp 1.2s ease 300ms;
    animation-fill-mode: forwards;
  }

  .page1 {
    background: url("https://my-homepage-1302786361.cos.ap-guangzhou.myqcloud.com/images/bg_2.jpg") center center no-repeat;
    background-size: 100%;
    width: 100%;
    min-width: 1420px;
    height: 100%;

    @keyframes changeBGimg {
      0% {
        background: url("https://my-homepage-1302786361.cos.ap-guangzhou.myqcloud.com/images/bg_2.jpg") center center no-repeat;
        background-size: 100%;
      }

      33% {
        background: url("https://my-homepage-1302786361.cos.ap-guangzhou.myqcloud.com/images/bg_1.jpg") center center no-repeat;
        background-size: 100%;
      }

      66% {
        background: url("https://my-homepage-1302786361.cos.ap-guangzhou.myqcloud.com/images/bg_3.jpg") center center no-repeat;
        background-size: 100%;
      }

      100% {
        background: url("https://my-homepage-1302786361.cos.ap-guangzhou.myqcloud.com/images/bg_2.jpg") center center no-repeat;
        background-size: 100%;
      }
    }

    animation: changeBGimg 10s infinite 2.5s;

    .wrap {
      height: 100%;
      display: flex;
      align-items: center;
      justify-content: center;

      .main {
        padding: 20px;
        opacity: 0;
        width: 600px;
        height: 250px;
        border-radius: 10px;
        background: rgba(255, 255, 255, 0.3);
        box-shadow: 0 0 50px #111;
        animation: fadeInUp 1.2s ease 1000ms;
        animation-fill-mode: forwards;
        transition: 600ms;
        text-align: center;

        .main-title {
          font-family: netsrak;
          cursor: default;
          transition: 600ms;
        }

        p {
          font-family: youzai;
          font-size: 30px;
          line-height: 42px;
          cursor: default;
          transition: 600ms;
        }
      }

      .main:hover {
        padding: 10px;
        background: rgba(255, 255, 255, 0.8);
        height: 300px;

        p {
          font-size: 35px;
        }

        .main-title {
          font-size: 35px;
        }
      }
    }
  }



  .nav_btn {
    position: fixed;
    top: 50px;
    right: 50px;
    width: 60px;
    height: 60px;
    line-height: 60px;
    text-align: center;
    border-radius: 50%;
    font-size: 35px;
    position: absolute;
    cursor: pointer;
    box-shadow: 0px 3px 1px rgba(0, 0, 0, 0.2);
    background: transparent;
    color: #ddd;
    z-index: 101;
    transition: 0.6s;
  }

  .nav_btn:hover {
    background: #409eff;
  }

  .nav_list {
    padding-top: 300px;
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    z-index: 100;
    background-color: white;
    overflow: hidden;
    transition: 0.6s;
    width: 300px;

    .nav_list-icon {
      font-size: 18px;
      display: inline-block;
      width: 30px;
      line-height: 100%;
    }
  }

  .message_btn {
    position: fixed;
    left: 50px;
    bottom: 50px;
    z-index: 99;
  }
</style>

<style lang="less">
  @keyframes shadowFadeIn {
    from {
      box-shadow: 0 0 0 0 #409eff;
    }

    to {
      box-shadow: 0 0 0 10px rgba(37, 143, 184, 0);
    }
  }

  .my-bullet {
    width: 8px;
    height: 8px;
    border: 3px solid #ddd;
    background-color: rgba(255, 255, 255, 0.7);
    border-radius: 50%;
    margin: 20px;
  }

  .my-bullet-active {
    background-color: #409eff;
    animation: shadowFadeIn 1.2s ease infinite;
  }
</style>
