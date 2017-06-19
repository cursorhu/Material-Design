Material Design（卡片式材料设计）是谷歌在I/O 2014上发布的新的设计语言。在Material的扁平化设计中，它使用了分层元素来营造三维空间。

该主题有Light和Dark两种显示模式，可通过toolBar右侧的按钮切换。博客可在主题文件theme.json中作简单的修改，theme.json文件内容如下：
```javascript
{
    ...
    "WebImgName": "leanote.png",
    "Color": "blue",
    "ColorStrength": "300",
    "BlogImg": "material.jpg",
    "FriendLinks": [
        {"Title": "My Note", "Url": "https://leanote.com/note"},
        {"Title": "Leanote Home", "Url": "https://leanote.com"},
        {"Title": "Leanote BBS", "Url": "http://bbs.leanote.com"},
        {"Title": "Leanote Github", "Url": "https://github.com/leanote/leanote"}
    ]
}
```
<!--more-->
主题预览：

![36585044-file_1493261409300_b2ea.png](https://github.com/wuyouzhuguli/Material-Design/blob/master/images/screenshot.png)


**2017年3月20日**

修复了几处在火狐浏览器下的bug。

**2017年3月23日**

修复Markdown下点击文章导航不跳转问题。
