### webFont vue 引入自定义字体

1. 先按您所需的字体去站长之家下载 http://font.chinaz.com/
2. 创建 font.css
```
@font-face {
  font-family: "bebasneue-webfont";
  src: url('bebasneue-webfont.woff2') format('woff2'),
       url('bebasneue-webfont.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
```
3. vue 要在app.vue 下import引入 普通h5下直接link 引入就行
```
@import "./common/font/font.css"; // 引入字体
```
4. 直接就可以在项目使用了
```
p{
  font-family:"bebasneue-webfont";
}
```
如果设置字体没有起作用 [点我](https://www.fontsquirrel.com/tools/webfont-generator "点我") 下载全部字体包 里面有demo
点这个上传一个刚刚在站长之家下载的字体
![点这个上传一个刚刚在站长之家下载的字体](http://47.98.201.115/file/6c28593a78b8eb6ecd3cc4bfa072b27.png)
点这个下载全部字体
![点这个下载全部字体](http://47.98.201.115/file/98d629e6c6823c128527475b42bc399.png)
