## 用css美化hover的underline下划线
众所周知，a:hover的下划线(underline)非常生硬，尝试给下划线加个动画？<br>
此项目将underline实现了点击时从中间展开效果。

## 文件说明
1.`hover.css`实现了自适应（主要是PC端hover，PE端改成了active）<br>
2.`hover.min.css`不需要自适应的直接引入这个就行了（默认hover）

## 使用方法
1.引入hover.css或者将源码加入到公共css文件中；<br>
2.给需要加入下划线的元素添加`hover`类:<br>
   ```css
   class="hover"
   ```
   ```css
    <a href="/" class="hover"></a>
    <p class="hover"></p>
   ```
## 注意事项
1.如果您的源代码已经定义了`a:hover`样式可能会导致双重的下划线，请尝试删除原来定义的`a:hover`样式再试！<br>
2.必须添加`hover`类，否则动画不会显示！<br>
3.其他的看注释吧,,,
