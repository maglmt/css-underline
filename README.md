## hover underline美化
hover效果的默认下划线(underline)效果展示非常生硬<br>
此项目为underline添加了一个展开特效。

## 文件说明
1.`hover.css`电脑/移动端自适应<br>
2.`hover.min.css`适用无自适应需求

## 使用方法
1.引入hover.(min).css文件；<br>
2.给需要添加下划线特效的元素添加`hover`类:<br>
   ```css
   class="hover"
   ```
   ```css
    <a href="/" class="hover"></a>
    <p class="hover"></p>
   ```
## 注意事项
1.如果源码已经定义了`a:hover`样式可能会导致双下划线，请尝试删除原来定义的`a:hover`样式<br>
```css
    <a href="/"></a>
    <p></p>
   ```
