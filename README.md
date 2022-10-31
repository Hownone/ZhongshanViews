##  

## 开源图标库

http://www.fontawesome.com.cn/
```
    <!-- font-awesome icons -->
    <link href="css/font-awesome.css" rel="stylesheet">
    <!-- //font-awesome icons -->
```

## 幻灯片插件 ResponsiveSlides
```
  <script src="js/responsiveslides.min.js"></script>
                        <script>
                            $(() => {
                                $("#slider4").responsiveSlides({
                                    auto: true,
                                    pager: true,
                                    nav: true,
                                    speed: 500,
                                    namespace: "callbacks",
                                });
                            })
  </script>
```

![ResponsiveSlides_api.png](https://cdn.acwing.com/media/article/image/2022/10/31/118375_ed6c134358-ResponsiveSlides_api.png)

## 平滑滚动插件：SmoothScroll

http://iamdustan.com/smoothscroll/

## 视差滚动插件： Jarallax

```
 <script src="js/jarallax.js"></script>
    <script type="text/javascript">
        /* init Jarallax */
        $('.jarallax').jarallax({
            speed: 0.5,
        })
 </script>
```

![Jarallax_api.png](https://cdn.acwing.com/media/article/image/2022/10/31/118375_dbba2ed158-jarallax_api.png)



## 滑动向上插件move-top.js & 过渡动画效果插件 easing.js

```javascript
 <script type="text/javascript" src="js/move-top.js"></script>
    <!-- 动画缓动函数 -->
    <script type="text/javascript" src="js/easing.js"></script>
    <!-- 向上滑动小图标 -->
    <script type="text/javascript">
        $(document).ready(() => {
            $().UItoTop({
                easingType: 'easeOutQuart'
            });
        });
 </script>详细
```



