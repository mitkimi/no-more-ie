# no-more-ie
放弃IE - 旧版本IE提醒更新浏览器

##使用：
在当前项目所有页面<head>标签里加入以下代码：
    &lt;!--[if lte IE 8]&gt;
       &lt;script&gt;
        window.location.href="ie.html";
       &lt;/script&gt;
    &lt;![endif]--&gt;

##反馈：
请联系：mitkimi@163.com
