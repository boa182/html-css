
# 我在工作当中做过的一些html+css的小案例
1.**纯Css导航下划线跟随效果（详细解说可以看chokcoco大大的博客）**
-  <a href="http://htmlpreview.github.com/?https://github.com/boa182/html-css/blob/master/html/03%E5%AF%BC%E8%88%AA%E4%B8%8B%E5%88%92%E7%BA%BF%E8%B7%9F%E9%9A%8F%E6%95%88%E6%9E%9C.html">demo点我吖</a>

2.**纯CSS波浪效果**
- 用途：可以用来展示任务完成百分比，或者标题背景动画
- 思路：
```html
<div>
<!-- 最外层的这个div设置overflow：hidden -->
    <div>
        <!-- 次外层的这个div给背景颜色，这个颜色就是用来做波浪的颜色 -->
        <div class="rotate">
            <!--旋转div，border-radius设45%，给个无限旋转的动画  -->
        </div>
    </div>

</div>
```
- <a href="http://htmlpreview.github.com/?https://github.com/boa182/html-css/blob/master/html/04%E7%BA%AFcss%E5%AE%9E%E7%8E%B0%E6%B3%A2%E6%B5%AA%E6%95%88%E6%9E%9C.html">波浪demo</a>

3.**鼠标悬浮图片滑动文字效果**
- 思路：
```html
    <!-- li设置overflow:hidden;position:relative;
         p设置position:absolute;
         通过改变li 的hover前后，p的bottom/top值，+transition实现滑动效果
         注意的是，背景颜色透明，但字体不透明，需要用到 rgba(33, 33, 33, 0.8);    
    -->
    <li>
      <img src="https://ss0.bdstatic.com/-0U0bnSm1A5BphGlnYG/tam-ogel/c70247aeafbe5a4699b0223bc8dd6fe4_222_222.jpg">
      <p>美的是一家领先的消费电器、暖通空调、机器人及工业自动化系统的科技企业集团</p>
    </li>
```
- <a href="http://htmlpreview.github.com/?https://github.com/boa182/html-css/blob/master/html/05%E9%BC%A0%E6%A0%87%E6%82%AC%E6%B5%AE%E5%9B%BE%E7%89%87%E5%88%92%E5%8A%A8%E6%96%87%E5%AD%97%E6%95%88%E6%9E%9C.html">demo1</a>
- <a href="http://htmlpreview.github.com/?https://github.com/boa182/html-css/blob/master/html/05-2%E9%BC%A0%E6%A0%87%E6%82%AC%E6%B5%AE%E5%9B%BE%E7%89%87%E6%BB%91%E5%8A%A8%E6%96%87%E5%AD%97%E6%95%88%E6%9E%9C.html">demo2</a>
