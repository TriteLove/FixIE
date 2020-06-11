# 常见的CSS兼容IE写法

## 背景渐变 
```css
  /* fix IE8+ */
  -ms-filter: 'progid:DXImageTransform.Microsoft.Gradient(startColorStr="#000000000", endColorStr="#99000000", GradientType=1)';
  /* normal */
  background-image: linear-gradient( to right, rgba(0, 0, 0, 0) 0%, rgba (0, 0, 0, 0.5625) 100% );
```