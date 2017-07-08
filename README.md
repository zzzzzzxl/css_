css的居中方式有很多种
* 文本居中 text-align
* margin居中 0 auto
* 定位属性居中 

这里说的是margin来居中，建议减少定位position的使用。

会用到的css属性

```
# 最小宽度
min-width: 1200px;

# 最大宽度
max-width: 1920px;
```

效果图
![](http://osp90rpxy.bkt.clouddn.com/17-7-8/60886452.jpg)

banner及footer属性
```
width: 100%;
min-width: 1200px;
max-width: 1920px;
```

公用容器类container：
```
.container {
  width: 1000px;
  margin: 0 auto;
}
```

> 源码（放在github）
  git 地址 https://github.com/zzzzzzxl/css_
