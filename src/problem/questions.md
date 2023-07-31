# 常见问题

遇到了什么问题，可以先来这里查找，如果没有找到，请提 issues:
[Github](https://github.com/ialley-workshop-open/uni-halo/issues)丨
[Gitee](https://gitee.com/ialley-workshop-open/uni-halo/issues)

## 常见问题与解决方案

### **1、如何解决在外置的浏览器调试出现跨域问题？**

<br/>答：在项目目录找到`common/http/index.js` 文件中的第`23-24`行代码，将代码注释掉即可，如下所示：

```javascript
// 如果是在外部浏览器调试或者编译为h5，请注释该行代码
// config.baseURL = HaloConfig.apiUrl;
```

### **2、将项目编译为 H5（web）应用时候，跨域如何解决？**

<br/>答：在项目目录找到`common/http/index.js` 文件中的第`23-24`行代码，将代码注释掉即可，如下所示：

```javascript
// 如果是在外部浏览器调试或者编译为h5，请注释该行代码
// config.baseURL = HaloConfig.apiUrl;
```

### **3、如何进入`halo`后台的静态存储上传文件？**

<br/>答：登录 halo 后台后，连续点击左上角的 logo 区域 10 次左右，即可开启` 开发者选项`， 开发者选项打开后，点击菜单`系统-小工具` 就可以看到开发者选项了，点击进入按钮，看到静态存储就可以上传你的文件了，这里的文件会跟你的系统主题在同级目录。

### **4、附件无法下载，去哪里获取？**

<br/>答：加 uni-halo 交流群，群号 `632969367`，群里有相关的素材可以下载，还可以在线交流。

### **5、配置图片防盗链后微信小程序图片无法访问？**

<br/>答：在防盗链的白名单中加入 `servicewechat.com` 和 `https://servicewechat.com` 链接，这两个链接是微信官方的地址，可以放心添加。如下图所示：
![微信小程序解决防盗链配置](https://img.925i.cn/file/a4626ffe387376d49da0b.png)

更多常见问题待补充...
