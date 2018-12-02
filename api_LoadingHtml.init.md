## 初始化 LoadingHtml ` LoadingHtml.init(); `

```
// 参数 1 config:{loading_time:1000} 遮罩层加载时间
// 参数 2 loading_mask_style 蒙版样式、与 CSS 一致
// 参数 3 loading_img_style 加载图片样式、与 CSS 一致
// 注意：以 - 连接的 CSS 属性 需用引号引起、如 'z-index'
var loading_mask=LoadingHtml.init({
    config:{},
    loading_mask_style:{},
    loading_img_style:{},
});
```