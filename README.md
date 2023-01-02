## JQRoll

JQRoll 是作者 Wybing 仿照朝夕光年官网开发出来的一款移动端、PC 端全屏图片滚动插件

## 基本使用

- 1.在 body 中添加 div

```html
<div id="main"></div>
```

- 2.在game_data中配置参数

```html
<script>
  $(document).ready(function () {
    $("#main").jqroll({
      /*
            Author:wybing
            date:2022-12-20
            

            【使用方法】
            1.插入<div id="main"></div>
            2.完成如下数据配置
            game_data: [
            {
              name:'',  // 标题文字
              isHot:false, // 是否加Hot图标
              icon:'', // 图标、logo
              small_bg:,  // 小图
              big_bg:,  // 大图
              desc:,  // 标题描述
              url:,   // 跳转地址
              date:,  // 右侧日期
            },
          */

      game_data: [
        {
          name: "这是一个Demo",
          isHot: true,
          icon: "https://lf3-fe-tos.dailygn.com/obj/g-marketing-act-assets/2021_10_29_16_24_59/1427026087467_s176746.png",
          small_bg:
            "https://lf3-fe-tos.dailygn.com/obj/g-marketing-act-assets/2021_08_13_14_30_00/306629162620_s78345.jpeg",
          big_bg:
            "https://lf3-fe-tos.dailygn.com/obj/g-marketing-act-assets/2021_08_16_11_59_23/722348965502_s691668.jpg",
          desc: "这是一个Demo，托管于vercel",
          url: "https://www.cnblogs.com/wybing",
          date: "01/01",
        },
      ],
    });
  });
</script>
```

