<h1 align="center">HeNy007 Preloader</h1>


## الخطوة الأولى 
ابحث في القالب عن وسم 
</ body>           
و ضع الكود فوقه مباشرة

```js

<script>
       $(window).on("load", function() {

 $(".preloader").fadeOut("slow")

 })


    </script>

```

## الخطوة الثانية
ابحث في القالب عن وسم
</ head>      
و ضع الكود فوقه مباشرة

```scss
<style>

  .preloader {

  position: fixed;

  left: 0;

  top: 0;

  z-index: 999;

  width: 100%;

  height: 100%;

  background: #fff url("https://heny007.github.io/loading-45.gif");

  background-repeat: no-repeat;

  background-position: center center;

  background-size: contain;

  background-attachment: fixed;

  }

  </style>
```
