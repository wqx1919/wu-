# wu-
一些问题
2022年1月11日19点49分
我遇到的第一个问题的理解就是vue，没有好
怎么弄显示内容，然后我在app.vue里面不先跳转路由
<router-link active-class="active" to="/register">Register</router-link>
只写展示
<router-view></router-view>
一切都完美了
2022年1月11日19点51分
可以用v-if来然后导航的选项是否显示注册和登录
2022年1月12日10点45分
图标字体无法引入；
解决办法：在css @import './font/iconfont.css';
上午的问题
回到顶部无法显示
解决办法：
  <el-backtop 
    :target=idname
    :bottom="100" 
    :visibility-height="1">
    <div
      style="{
        height: 100%;
        width: 100%;
        background-color: #f2f5f6;
        box-shadow: 0 0 6px rgba(0,0,0, .12);
        text-align: center;
        line-height: 40px;
        color: #1989fa;
      }"
    >
      UP
    </div>
  </el-backtop>
  注意点：其中target是默认没有v-bing 事件的，只不过我是把它分成了组件次在后面传值过来要用到的
  说到这个传值我就忘记了要加v-bing 也就是：s  
  r2022年1月13日16点42分
