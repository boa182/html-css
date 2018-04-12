
# 我在工作当中做过的一些html+css的小案例
1.**纯Css导航下划线跟随效果（详细解说可以看chokcoco大大的博客）**
-  <a href="http://htmlpreview.github.com/?https://github.com/boa182/html-css/blob/master/html/03%E5%AF%BC%E8%88%AA%E4%B8%8B%E5%88%92%E7%BA%BF%E8%B7%9F%E9%9A%8F%E6%95%88%E6%9E%9C.html">demo点我吖</a>

2.**纯CSS波浪效果（可以用来做完成度或标题背景动画）**
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