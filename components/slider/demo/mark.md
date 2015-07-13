# 分段式滑块

- order: 3

使用 `marks` 属性标注分段式滑块，结合 `index` 可以指定滑块按钮初始位置。

---

````jsx
var Slider = antd.Slider;

React.render(
  <Slider marks={["状态1","状态2","状态3","状态4"]} index={1}/>
, document.getElementById('components-slider-demo-mark'));
````
