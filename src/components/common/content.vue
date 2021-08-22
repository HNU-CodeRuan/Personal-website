<template>
  <div class="content-bd">

    <div class="content-love">
      <section class="skill">
        <header class="section-hd">
          <span class="section-title-l"></span>
          <h2 class="section-title">个人爱好</h2>
          <span class="section-title-r"></span>
        </header>
        <div class="section-bd">
          <div class="ui container">

                <div class="ui stackable grid">
                  <div class="eleven wide column">
                    <div class="ui segment">
                      <img src="https://pic2.zhimg.com/v2-13d9d3e944c4384d22eb848c386f73ab_r.jpg?source=1940ef5c" alt="" class="ui rounded image">
                    </div>
                  </div>
                  <div class="five wide column">
                    <div class="ui top attached segment">
                      <div class="ui header">关于我</div>
                    </div>
                    <div class="ui attached segment">
                      <p class="m-text">誓将学习无限循环. 希望结识可以共同成长的小伙伴.</p>

                    </div>
                    <div class="ui attached segment">
                      <div class="ui orange basic left pointing label">编程</div>
                      <div class="ui orange basic left pointing label">唱歌</div>
                      <div class="ui orange basic left pointing label">思考</div>
                      <div class="ui orange basic left pointing label">书法</div>
                      <div class="ui orange basic left pointing label">文学</div>
                      <div class="ui orange basic left pointing label">历史</div>
                    </div>
                    <div class="ui attached segment">
                      <div class="ui teal basic left pointing label m-margin-tb-tiny">Java</div>
                      <div class="ui teal basic left pointing label m-margin-tb-tiny">JavaScript</div>
                      <div class="ui teal basic left pointing label m-margin-tb-tiny">Node</div>
                      <div class="ui teal basic left pointing label m-margin-tb-tiny">React</div>
                      <div class="ui teal basic left pointing label m-margin-tb-tiny">Python</div>
                      <div class="ui teal basic left pointing label m-margin-tb-tiny">MYSQL</div>
                      <div class="ui teal basic left pointing label m-margin-tb-tiny">...</div>
                    </div>
                    </div>
                </div>

              </div>






        </div>
      </section>

    </div>







    <div class="content-left">
      <section class="practice">
        <header class="section-hd">
          <span class="section-title-l"></span>
          <h2 class="section-title">项目经历</h2>
          <span class="section-title-r"></span>
        </header>
        <div class="section-bd">
          <div class="item">
            <header class="item-hd">
              <h3 class="item-name">所有项目</h3>
              <span class="item-time">2018.01 至 2021.05</span>
              <a class="btn item-more"
                 href=""
                 target="_blank" title="点击查看->西安绿豆芽信息科技有限公司百度百科">项目</a>
            </header>
            <ol class="item-project">
              <li class="project-1">
                <h3 class="project-name">
                  <a href="" target="_blank"
                     title="">是题霸</a></h3>
                <ol>
                  <li class="project-2">
                    <div class="item-bd">
                      <h3 class="project-name-2">是题霸后端</h3>
                      <div class="div-item">
                        <h3 class="project-des">【项目简介】</h3>
                        <p class="item-project-des">
                          该项目主要分为学生端（学生答题、测试、讨论）、教师端（教师答疑、任务发布、成绩导出与班级管理）与管理端（用户管理、反馈管理）——三端合一的小程序。以Wechat为载体，并依托微信强大的社交与引流能力，以及它所提供的云开发为项目提供技术支撑。</p>
                      </div>
                      <div class="div-item">
                        <h3 class="project-des">【工作职责】</h3>
                        <ul class="section-content">
                          <li>负责项目框架搭建以及疑难问题解决，为项目成员提供开发思路</li>
                          <li>主导整个项目正常开发流程，研究了高可用、高并发服务器的架构设计（keepalived+nginx+haproxy）</li>
                          <li>对常用数据进行缓存处理（Redis），并对[撮合引擎]系统进行了架构设计，采用Redis内存撮合、Rabbit MQ消息队列异步入库实现高性能撮合系统，从而实现撮合引擎弹性伸缩
                          </li>
                          <li>
                            针对Redis可能出现脏读的问题可以采用消息队列处理，消除多线程同一时间操作同一Redis数据的脏读问题；或可以通过Redis锁解决高并发的脏读问题（不推荐，可能会造成无效等待）
                          </li>
                        </ul>
                      </div>
                    </div>
                  </li>
                  <li class="project-2">
                    <div class="item-bd">
                      <h3 class="project-name-2">是题霸前端</h3>
                      <div class="div-item">
                        <h3 class="project-des">【项目简介】</h3>
                        <p class="item-project-des">该项目前端开发框架采用目前市面流行的Vue.js框架与Element UI
                          2.0。K线、行情等数据全通过websocket进行数据传输，解决了大量数据通过http请求造成服务端压力过大的问题，也保证了数据的时效性；K线图表采用国外TradingView工具，高效且专业的解决企业在数据图表绘制的问题；在应用数据存储上采用vuex实现多页面数据共享。</p>
                      </div>
                      <div class="div-item">
                        <h3 class="project-des">【工作职责】</h3>
                        <ul class="section-content">
                          <li>负责项目框架搭建以及疑难问题解决，为项目成员提供开发思路</li>
                          <li>主导整个项目正常开发流程，研究K线渲染组件TradingView的使用与原理</li>
                        </ul>
                      </div>
                    </div>
                  </li>

                </ol>
              </li>
              <li class="project-1">
                <h3 class="project-name">
                  <a href="http://www.bitchang.com" target="_blank"
                     title="点击进入->数字货币钱包">数字货币钱包</a>
                </h3>
                <ol>
                  <li class="project-2">
                    <div class="item-bd">
                      <h3 class="project-name-2">厚学LNPU</h3>
                      <div class="div-item">
                        <h3 class="project-des">【项目简介】</h3>
                        <p class="item-project-des">
                          该项目是一款服务校园的小程序，为辽宁石油化工大学学生提供二手物品交易平台、快递代取、交友社区等便利服务</p>
                      </div>
                      <div class="div-item">
                        <h3 class="project-des">【工作职责】</h3>
                        <ul class="section-content">
                          <li>负责项目后端接口开发</li>
                          <li>提供API以及JSON RPC文档实现订单查询、积分兑现、充值等逻辑</li>
                        </ul>
                      </div>
                    </div>
                  </li>
                </ol>
              </li>
              <li class="project-1">
                <h3 class="project-name">
                  <a href="http://www.ledianyun.com/" target="_blank"
                     title="点击进入->乐店云商城系统">乐店云商城系统</a>
                </h3>
                <ol>
                  <li class="project-2">
                    <div class="item-bd">
                      <h3 class="project-name-2">后台开发(PHP)</h3>
                      <div class="div-item">
                        <h3 class="project-des">【项目简介】</h3>
                        <p class="item-project-des">
                          <a href="https://baike.baidu.com/item/%E4%B9%90%E5%BA%97%E4%BA%91" target="_blank"
                             title="点击查看->乐店云百度百科">乐店云</a>是一个专门为商户提供新零售智慧店铺解决方案的<a href="https://www.ledianyun.com/"
                                                                                   target="_blank" title="乐店云官网">一站式小程序生成平台</a>。项目主要采用PHP+Phalcon+Mysql框架，包含分销、砍价、拼团等营销以及基础的商城功能。
                        </p>
                      </div>
                      <div class="div-item">
                        <h3 class="project-des">【工作职责】</h3>
                        <ul class="section-content">
                          <li>负责拼团功能开发，该功能主要涉及用户与用户共同下单逻辑，需要保证在库存无误的情况下，实现多用户订单的提交与交易的正常进行</li>
                          <li>负责官网的开发以及官网搜索引擎优化</li>
                        </ul>
                      </div>
                    </div>
                  </li>
                </ol>
              </li>
            </ol>
          </div>




        </div>

      </section>
    </div>


    <div class="content-right">
      <section class="skill">
        <header class="section-hd">
          <span class="section-title-l"></span>
          <h2 class="section-title">技能</h2>
          <span class="section-title-r"></span>
        </header>
        <div class="section-bd">

          <!--技能:WEB后端开发-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">WEB后端开发</span>
              <a class="btn item-more">熟练掌握</a>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>后端应用Java、Python实际开发经验，掌握Java面向对象思想编程</li>
                <li>熟练使用Spring Boot、SpringMVC等主流框架，熟悉Restful 风格API设计</li>
                <li>熟练使用数据库操作框架Hibernate JPA，掌握SQL语句增删改查</li>
                <li>熟练使用Websocket，并使用websocket进行服务端与客户端实时数据传输</li>
                <li>熟练使用Jwt等用户鉴权产品</li>
                <li>熟悉API开发基本流程，熟悉Restful 风格API设计</li>
                <li>了解Spring cloud，正学习Spring cloud在企业大型应用中的应用，以及大型应用的微服务化及服务治理知识学习</li>
              </ul>
            </div>
          </div>

          <!--React-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">数据库</span>
              <a class="btn item-more">熟练掌握</a>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>熟悉关系型数据库技术，熟练使用关系型数据库Mysql、Oracle</li>
                <li>熟悉非关系型数据库技术，熟练使用非关系型数据库Nosql：Redis</li>
                <li>熟练使用Hibernate JPA，了解 MyBatis、JDBC等数据库操作框架使用</li>
              </ul>
            </div>
          </div>

          <!--服务器|架构-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">服务器|架构</span>
              <a class="btn item-more">熟练掌握</a>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>熟练掌握Nginx、Tomcat、Apache服务器使用</li>
                <li>熟练掌握常用软件（MySQL、Redis等）在服务器的搭建与使用</li>
                <li>熟练使用Centos(Linux)云服务器并掌握线上环境和应用的部署</li>
                <li>了解Docker使用及Docker应用部署</li>
                <li>熟练掌握Git、Github、gradle、maven等工具使用</li>
              </ul>
            </div>
          </div>

          <!--WEB前端开发-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">WEB前端开发</span>
              <a class="btn item-more">掌握</a>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>有一年以上Android原生开发经验，熟练掌握使用Java SE开发Android原生APP</li>
                <li>熟悉前端技术HTML、VUE、JS、CSS、Flutter，有实际项目中的前端开发、维护经验</li>
                <li>掌握网页重构所需的CSS、SCSS</li>
                <li>掌握前端流行框架Vue</li>
                <li>熟知JS基本语法与知识，熟悉JS语法</li>

          
              </ul>
            </div>
          </div>

          
          <!--Python-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">Python</span>
              <a class="btn item-more">熟悉</a>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>熟悉Python基本语法与标准库</li>
                <li>用Python开发过小型项目服务</li>
              </ul>
            </div>
          </div>

          <!--独立开发-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">独立开发</span>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>有独自主导并负责的项目开发经验，在项目中可进行独立开发</li>
                <li>有良好的编码习惯与编程思想，学习能力强，可快速学习新技术，对新技术、好技术热爱</li>
                <li>工作稳定性高，对公司负责，有一定的项目管理经验，有创业经历</li>
              </ul>
            </div>
          </div>

          
        </div>
      </section>




      <!--奖项/证书-->
      <section class="prize">
        <header class="section-hd">
          <span class="section-title-l"></span>
          <h2 class="section-title">奖项/证书</h2>
          <span class="section-title-r"></span>
        </header>
        <div class="section-bd">

          <!--技能:WEB后端开发-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">获奖经历</span>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>2021年8月获得“竞技世界杯”中国大学生计算机博弈大赛五子棋项目<span>全国季军</span></li>
                <li>2021年8月获得“竞技世界杯”中国大学生计算机博弈大赛爱恩斯坦棋项目<span>全国二等奖</span></li>
                <li>2021年7月通过计算机技术与软件专业技术资格（水平）中级考试获得<span>软件设计师中级职称</span></li>
                <li>2021年5月获得辽宁省计算机设计大赛<span>三等奖</span></li>
                <li>2020年9月获得全国移动互联创新大赛辽宁赛区<span>银奖</span></li>
                <li>2020年8月获得中国高校计算机大赛微信小程序应用开发赛东北赛区<span>二等奖</span></li>
                <li>2020年7月获得辽宁省计算机系统与程序设计大赛<span>三等奖</span></li>
              </ul>
            </div>
          </div>
        </div>
      </section>

      <!--致谢-->
      <section class="thanks">
        <header class="section-hd">
          <span class="section-title-l"></span>
          <h2 class="section-title">致谢</h2>
          <span class="section-title-r"></span>
        </header>
        <div class="section-bd">
          <!--技能:WEB后端开发-->
          <div class="item">
            <h2 style="font-weight: bold;line-height: 24px;margin-top: 10px">
              感谢您在百忙之中阅读这份履历，诚挚的期望能得到面试的机会，希望有荣幸能为公司效力！再次致以我最诚挚的谢意！！</h2>
          </div>
        </div>
      </section>

    </div>

  </div>
</template>

<style scoped>
  .item-bd span{
    color: orange;
    font-weight: bold;
  }
</style>

<script>
    import $ from 'jquery'

    export default {
        name: 'Content',
        components: {},
        data() {
            return {
                msg: 'Welcome to Your Vue.js App'
            }
        },
        mounted() {
            $(document).ready(function () {
                if ($('ol:first').css('list-style-type') == 'none') { /* For IE6/7 only. */
                    $('ol ol').each(function (i, ol) {
                        ol = $(ol);
                        var level1 = ol.closest('li').index() + 1;
                        ol.children('li').each(function (i, li) {
                            li = $(li);
                            var level2 = level1 + '.' + (li.index() + 1);
                            li.prepend('<span>' + level2 + '</span>');
                        });
                    });
                }
            });
        }
    }
</script>
