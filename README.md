# HTML PRACTISE
## add some background property
- background-color : #RRGGBB rgba( , , , )
- background-image: url(ballon.jpg)
- background-repeat: no-repeat/repeat-x/repeat-y/repeat
- background-position: top right,bottom,left
- background-size: cover,contain
- background-attachment: scrool/fixed/local
---
## others un-learnen background property
- background-blend-mode: 定义元素的背景图片，以及背景色如何混合。
  - 混合模式mix-blend-mode: normal;multiply;screen;overlay;darken;lighten;color-dodgecolor-burn;hard-light;soft-light;difference;exclusion;hue;saturation;color;luminosity;
- background-clip: 设置元素的背景（背景图片或颜色）是否延伸到边框、内边距盒子、内容盒子下面。
  - **border-box**
    背景延伸至边框外沿（但是在边框下层）。

  - **padding-box**
    背景延伸至内边距（padding）外沿。不会绘制到边框处。

  - **content-box**
    背景被裁剪至内容区（content box）外沿。

  - **text** 实验性
    背景被裁剪成文字的前景色。
- background-origin: 规定了背景图片的摆放位置
  - border-box：以border为参考
  - padding-box：以padding为参考
  - margin-box：以margin为参考
## display(box)
- block（块盒子）
- inline （内联盒子）
- inline-block （中间）