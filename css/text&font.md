- text-indent  
  文本块中首行文本的缩进
- text-transform  
  控制文本的大小写
  none	默认。定义带有小写字母和大写字母的标准的文本。
  capitalize	文本中的每个单词以大写字母开头。
  uppercase	定义仅有大写字母。
  lowercase	定义无大写字母，仅有小写字母。
  inherit	规定应该从父元素继承 text-transform 属性的值。
- text-decoration  
  none	默认。定义标准的文本。
  underline	定义文本下的一条线。
  overline	定义文本上的一条线。
  line-through	定义穿过文本下的一条线。
  blink	定义闪烁的文本。
  inherit	规定应该从父元素继承 text-decoration 属性的值。
- text-align  
  left	把文本排列到左边。默认值：由浏览器决定。
  right	把文本排列到右边。
  center	把文本排列到中间。
  justify	实现两端对齐文本效果。
  inherit	规定应该从父元素继承 text-align 属性的值。
- word-spacing  
  单词间的空白
- white-space  
  normal	默认。空白会被浏览器忽略。
  pre	空白会被浏览器保留。其行为方式类似 HTML 中的 <pre> 标签。
  nowrap	文本不会换行，文本会在在同一行上继续，直到遇到 <br> 标签为止。
  pre-wrap	保留空白符序列，但是正常地进行换行。
  pre-line	合并空白符序列，但是保留换行符。
  inherit	规定应该从父元素继承 white-space 属性的值。
- color  
  文字颜色
- line-height  
  行高
- font  
  font:italic bold 12px/20px arial,sans-serif;
- font-family  
  字体
- font-size  
  smaller	把 font-size 设置为比父元素更小的尺寸。
  medium
  larger	把 font-size 设置为比父元素更大的尺寸。
  - 大小  
    xx-small
    x-small
    small
    medium
    large
    x-large
    xx-large
    把字体的尺寸设置为不同的尺寸，从 xx-small 到 xx-large。
    默认值：medium。
- font-weight  
  bold	定义粗体字符。
  bolder	定义更粗的字符。
  lighter	定义更细的字符。
  - 数字表示大小  
    100~900：定义由粗到细的字符。400 等同于 normal，而 700 等同于 bold。
- font-face  
  引入字体  
  <pre>
    @font-face {
    font-family: 'hooray';  /*给自定义字体命名*/
    src: url('hooray.eot');
    src: url('hooray.eot?#iefix') format('eot'),
         url('hooray.woff') format('woff'),
         url('hooray.ttf') format('truetype'),
         url('hooray.svg#webfontjKg17VrE') format('svg');
    }
  </pre>
