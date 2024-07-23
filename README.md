<p>
    <a href="https://tailwindcss.com/" target="_blank">
      <img alt="Tailwind CSS" width="350" src="https://refactoringui.nyc3.cdn.digitaloceanspaces.com/tailwind-logo.svg">
    </a><br>
    一个小程序使用tailwind的解决方案
</p>


------

## 什么是weapp-tailwind

使用tailwind的2.2.19版本代码，经过一些操作后，生成一个小程序端适用的css文件。

> 操作主要包含：关闭base和components，将rem改为px，替换color为最新版本的tailwind的配色等。

## 为什么weapp-tailwind会产生

tailwind作为一优秀的css框架，可以显著提高前端程序员的效率，但是在小程序端不能直接使用tailwind，最主要的是1.5，1/2，[14px]这样的写法，小程序不支持，[weapp-tailwindcss](https://github.com/sonofmagic/weapp-tailwindcss)可以支持基本上tailwindcss的所有特性，但是它是将整个小程序的代码，包括wxml和wxss文件中的class都改了名，使用上比较重。而hover,focus等特征，其实在小程序端没什么用，在我看来，小程序端只需要工具类的样式，基于这些考虑，尝试了这个项目。

## 如何使用weapp-tailwind

在release页面，下载tailwind.css或tailwind.min.css，放入小程序，引入即可。
