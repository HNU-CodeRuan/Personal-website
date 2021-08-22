<template>
  <div>
    <!-- <v-head></v-head> -->
    <v-top-menu></v-top-menu>


    <v-swiper></v-swiper>
    <main class="content">
      
      <!--基本信息-->
      <v-base-info></v-base-info>
      <v-content></v-content>
    </main>
    <v-foot></v-foot>
  </div>
</template>

<script>
    import VHead from "./common/head.vue";
    import Aboutus from "./common/aboutus.vue"
    import topMenu from "./common/TopMenu.vue";
    import VBaseInfo from "./common/baseInfo.vue";
    import VContent from "./common/content.vue";
    import VFoot from "./common/foot.vue";

    export default {
        name: 'Resume',
        components: {
            "v-head": VHead,
            "v-swiper":Aboutus,
            "v-top-menu":topMenu,
            "v-base-info": VBaseInfo,
            "v-content": VContent,
            "v-foot": VFoot,
        },
        data() {
            return {
                msg: 'Welcome to Your Vue.js App'
            }
        }
    }
</script>
