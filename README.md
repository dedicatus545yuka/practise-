# practise-
用魅族商城页面来做的一些关于HTML,CSS的练习  
### 只是注重效果来写，忘了注释了，还有就是关于CSS的调整真的很坑爹啊但是为了美观也只能慢慢来了:cry:  
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>魅族商城的底部</title>
    <link rel="stylesheet" href="魅族商城底部.css">
</head>
<body>
<!-- 设置一个大容器再用两个容器来居中 -->
<div class="foot">
    <!-- 以边框为界设置上容器 -->
    <div class="foot-head">
        <!-- 在上容器中分左右两列实现效果 -->
        <div class="head-left">
            <!--在左列中使用两个列表来排列8个盒子-->
            <ul class="head-left-ul">
                <li class="head-left-li">
                    <a href="#" class="head-left-a">
                        <!--通过i标签来使用网络字体 -->
                        <i class="head-left-i-1 head-left-i"></i>
                        <span class="head-left-s">顺丰包邮</span>
                    </a>
                </li>
                <li class="head-left-li">
                    <a href="#" class="head-left-a">
                        <i class="head-left-i-2 head-left-i"></i>
                        <span class="head-left-s">100+城市次日送达</span>
                    </a>
                </li>
                <li class="head-left-li">
                    <a href="#" class="head-left-a">
                        <i class="head-left-i-3 head-left-i"></i>
                        <span class="head-left-s">7天无理由退货</span>
                    </a>
                </li>
                <li class="head-left-li">
                    <a href="#" class="head-left-a">
                        <i class="head-left-i-4 head-left-i"></i>
                        <span class="head-left-s">15天换货保障</span>
                    </a>
                </li>
            </ul>
            <ul class="head-left-ul">
                <li class="head-left-li">
                    <a href="#" class="head-left-a">
                        <i class="head-left-i-5 head-left-i"></i>
                        <span class="head-left-s">1年免费保修</span>
                    </a>
                </li>
                <li class="head-left-li">
                    <a href="#" class="head-left-a">
                        <i class="head-left-i-6 head-left-i"></i>
                        <span class="head-left-s">2300+线下体验店</span>
                    </a>
                </li>
                <li class="head-left-li">
                    <a href="#" class="head-left-a">
                        <i class="head-left-i-7 head-left-i"></i>
                        <span class="head-left-s">远程支持服务</span>
                    </a>
                </li>
                <li class="head-left-li">
                    <a href="#" class="head-left-a">
                        <i class="head-left-i-8 head-left-i"></i>
                        <span class="head-left-s">上门快修</span>
                    </a>
                </li>
            </ul>
        </div>
        <div class="head-right">
            <p class="head-right-p">24小时全国服务热线</p>
            <a href="tel:400-788-3333" class="head-right-a-tel">400-788-3333</a>
            <a href="#" class="head-right-a-kefu">
                <i class="head-right-i"></i>
                <span class="head-right-s">在线客服</span>
            </a>
        </div>
    </div>
    <!-- 以边框为界设置下容器 -->
    <div class="foot-bottom">
        <!-- 在下容器中通过两个列表实现显示效果 -->
        <ul class="foot-bottom-top">
            <li class="bottom-top-li-1">
                <a href="#" class="bottom-top-a">了解魅族</a>
            </li>
            <li class="bottom-top-li">
                <a href="#" class="bottom-top-a">加入我们</a>
            </li>
            <li class="bottom-top-li">
                <a href="#" class="bottom-top-a">联系我们</a>
            </li>
            <li class="bottom-top-li">
                <a href="#" class="bottom-top-a">flyme</a>
            </li>
            <li class="bottom-top-li">
                <a href="#" class="bottom-top-a">魅族社区</a>
            </li>
            <li class="bottom-top-li">
                <a href="#" class="bottom-top-a">天猫旗舰店</a>
            </li>
            <li class="bottom-top-li">
                <a href="#" class="bottom-top-a">问题反馈</a>
            </li>
            <li class="bottom-top-li">
                <a href="#" class="bottom-top-a">线上销售授权名单公示</a>
            </li>
        </ul>
        <ul class="foot-bottom-btm">
            <li class="btm-li-left btm-li-left-text-1">
                ©2017 Meizu Telecom Equipment Co., Ltd. All rights reserved.
            </li>
            <li class="btm-li-left btm-li-left-text">
                <a href="#" class="btm-a">
                    粤ICP备13003602号-2
                </a>
            </li>
            <li class="btm-li-left btm-li-left-text">
                <a href="#" class="btm-a">
                    合字B2-20170010
                </a>
            </li>
            <li class="btm-li-left btm-li-left-text">
                <a href="#" class="btm-a">
                    营业执照
                </a>
            </li>
            <li class="btm-li-left btm-li-left-text">
                <a href="#" class="btm-a">
                    法律声明
                </a>
            </li>
            <li class="btm-li-left btm-li-left-text">
                粤公网安备 44049102496009 号
            </li>
            <li class="btm-li-left btm-li-left-img">
                <a href="#" class="btm-a btm-a-1"></a>
            </li>
            <li class="btm-li-left btm-li-left-img">
                <a href="#" class="btm-a btm-a-2"></a>
            </li>
            <li class="btm-li-left btm-li-left-img">
                <a href="#" class="btm-a btm-a-3"></a>
            </li>
            <li class="btm-li-right btm-li-right-b">
                <a href="#" class="btm-a">
                    <i class="btm-a-i-1 btm-a-i"></i>
                </a>
            </li>
            <li class="btm-li-right btm-li-right-b">
                <a href="#" class="btm-a">
                    <i class="btm-a-i-2 btm-a-i"></i>
                </a>
            </li>
            <li class="btm-li-right">
                <a href="#" class="btm-a">
                    <i class="btm-a-i-3 btm-a-i"></i>
                </a>
            </li>
        </ul>
    </div>
</div>
</body>
</html>
```

`魅族商城底部.css`

```CSS
body {
    margin: 0px;
}
@font-face {
    /* 定义网络字体的字体系列名称 */
    font-family: layout-font;
    /* 引入指定的网络字体文件 */
    src: url(https://store.res.meizu.com//layout/font/iconfont-7fe3aaa151.eot);
    src: url(https://store.res.meizu.com//layout/font/iconfont-7fe3aaa151.eot#iefix) format("embedded-opentype"), url(https://store.res.meizu.com//layout/font/iconfont-d91c6d8c6e.woff) format("woff"), url(https://store.res.meizu.com//layout/font/iconfont-43e1f7b40d.ttf) format("truetype")
}
ul {
    margin: 0;
    padding:0;
    font-weight: 400;
    list-style: none;
    overflow: hidden;
    /* 覆盖掉浏览器默认的ul格式 */
}
a {
    text-decoration: none;
    /* 去除a标签带来的下划线 */
}
p {
    margin: 0;
    padding: 0;
    list-style: none;
    font-weight: 400;
    /* reset默认的样式 */
}
i {
    font-family: layout-font !important;
    /* 设置i标签的字体样式 */
    vertical-align: middle;
    /* 垂直居中 */
    font-style: normal;
    text-align: center;
}
.foot {
    width: 1423px;
    /* 给整个大容器定宽 */
}
.foot-head {
    width: 1240px;
    margin: 80px auto 20px;
    /* 设置居中容器的基本样式 */
    overflow: hidden;
    /* 解决高度塌陷的问题 */
    border-bottom: 1px solid #efefef;
    /* 通过设置下边框来显示分开上下两个盒子 */
}
.head-left {
    float: left;
    /* 设置浮动让盒子水平左排列 */
}
.head-left-ul{
    margin-bottom: 27px;
}
.head-left-li {
    float: left;
    width: 154px;
    margin-right: 60px;
    /* 设置浮动让盒子可以脱离文档流水平排列 */
}
.head-left-a {
    color: #999;
}
.head-left-i {
    font-size: 30px;

}
.head-left-s {
    font-size: 14px;
}
.head-left-i-1::before {
    content: "\E631";
    /* 给元素设置伪类引入网络字体 */
}
.head-left-i-2::before {
    content: "\E62C";
}
.head-left-i-3::before {
    content: "\E62D";
}
.head-left-i-4::before {
    content: "\E62E";
}
.head-left-i-5::before {
    content: "\E62F";
}
.head-left-i-6::before {
    content: "\E632";
}
.head-left-i-7::before {
    content: "\E630";
}
.head-left-i-8::before {
    content: "\E633";
}
.head-right {
    float: right;
    /* 让盒子右浮动，在容器右边 */
    text-align: right;
    /* 文本水平居中 */
}
.head-right-p {
    font-size: 12px;
    margin-bottom: 2px;
    color: #999;
    /* 给文字设置基本样式 */
}
.head-right-a-tel {
    display: block;
    font-size: 20px;
    color: #00c3f5;
    margin-bottom: 8px;
}
.head-right-a-kefu {
    width: 140px;
    color: #fff;
    font-size: 16px;
    line-height: 36px;
    /* 设置行高 */
    text-align: center;
    display: block;
    background-color: #00c3f5;
    border-radius: 3px;
    /* 设置圆角 */
}
.head-right-a-kefu:hover {
    background-color: #40D2F8;
}
.head-right-i {
    font-size: 28px;
    margin-left: -4px;
}
.head-right-i::before {
    content: "\E629";
}
.head-right-s {
    display: inline-block;
    vertical-align: middle;
    margin-left: -6px;
}
.foot-bottom {
    width: 1240px;
    margin: 0 auto;
    font-size: 12px;
    color: #999;
}
.foot-bottom-top {
    margin: 26px 0 18px;
    /* 设置偏移量拉开距离 */
}
.bottom-top-li-1,.bottom-top-li {
    display: inline-block;
}
.bottom-top-li-1{
    padding-right: 15px;
}
.bottom-top-li {
    padding: 0 15px;
    border-left: 1px solid #efefef;
}
.bottom-top-a,.btm-a {
    color: #999;
    background-repeat: no-repeat;
    /* 背景平铺方式不重复 */
}
.foot-bottom-btm {
    width: 1240px;
    height: 20px;
}
.btm-li-left-text-1 {
    margin: 2.25px 10px 0 0;
}
.btm-li-left-text{
    margin: 2.25px 4px 0 0;
}
.btm-li-left-img {
    margin: 0px 3.5px 0;
}
.btm-li-left {
    float: left;
    /* 设置浮动让盒子水平排列且对齐方式不以文字对齐 */
}
.btm-li-right {
    float: right;
    width: 36px;
    text-align: center;
    margin-top: -3px;
}
.btm-li-right-b {
    border-left: 1px solid #efefef;
}
.btm-a-1,.btm-a-2,.btm-a-3 {
    display: block;
    width: 19px;
    height: 19px;
}
.btm-a-1 {
    background-image: url("http://a1.qpic.cn/psb?/V118JuTr3rHMrA/FPyAbxz8CDuQG9HITdpCHf4Z.BRhjNZyG6M01*28Rhw!/b/dPMAAAAAAAAA&bo=EAASAAAAAAADByA!&rf=viewer_4");
}
.btm-a-1:hover {
    background-image: url("http://a3.qpic.cn/psb?/V118JuTr3rHMrA/WVPE3VyurBrjtBJV1jykC96eftESI4Fbf5y*GGBxhFg!/b/dGoBAAAAAAAA&bo=EAASAAAAAAADACc!&rf=viewer_4");
}
.btm-a-2 {
    background-image: url("http://a1.qpic.cn/psb?/V118JuTr3rHMrA/pcVofX3TAn77vzZIq3xKa9*pOsmHlQ7nkCDMIk4jCR4!/b/dPMAAAAAAAAA&bo=EAASAAAAAAADACc!&rf=viewer_4");
}
.btm-a-2:hover {
    background-image: url("http://a1.qpic.cn/psb?/V118JuTr3rHMrA/hraA18D8*aeFGxV5xuMuMSJkhPYZBfUSJ6GEgmqVV7k!/b/dD4BAAAAAAAA&bo=EAASAAAAAAADACc!&rf=viewer_4");
}
.btm-a-3 {
    background-image: url("http://a1.qpic.cn/psb?/V118JuTr3rHMrA/Y72dt99kvX5.mHjXpLA82.ZYxEhzt*86FSa4hsmqkBo!/b/dGsBAAAAAAAA&bo=FAASAAAAAAADACM!&rf=viewer_4");
}
.btm-a-3:hover {
    background-image: url("http://a3.qpic.cn/psb?/V118JuTr3rHMrA/s42QXl9ZJXBbZ2SL8KyRW.SBpiD3EbK7sN0Nm4d3dS0!/b/dPIAAAAAAAAA&bo=FAASAAAAAAADACM!&rf=viewer_4");
}
.btm-a-i{
    font-size: 26px;
    transition: color 0.5s;
    /* 设置效果延迟（缓缓实现）*/
}
.btm-a-i-1::before {
    content: "\E61C";
}
.btm-a-i-1:hover {
    color: #ecc337;
}
.btm-a-i-2::before {
    content: "\E694";
}
.btm-a-i-2:hover {
    color: #6fc749;
}
.btm-a-i-3::before {
    content: "\E600";
}
.btm-a-i-3:hover {
    color: #ff6c6c;
}
```
### 还是附上一张实现的效果图吧  
![效果图](http://a4.qpic.cn/psb?/V118JuTr3rHMrA/zEoAHuQtJP0yPsELFAGNU*WUvDF7b7lsCiYStkQpJwQ!/m/dPMAAAAAAAAA&bo=JgpsAgAAAAADB2A!&rf=photolist)
