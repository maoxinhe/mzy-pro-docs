---
title: CMY 校验
permalink: /verify.html
classes: wide
toc: false
---

检查 CMY 文件是否是官方构建。

<div id="cmy-verify" class="notice">
  <div id="cmy-verify-alert">点击并选择文件或将文件拖拽到此处进行校验</div>
  <div id="cmy-verify-file"></div>
  <input id="cmy-verify-input" type="file" accept=".jar,.exe,.sh">
</div>

<style>
  #cmy-verify {
    gap: 2em;
    display: flex;
    cursor: pointer;
    user-select: none;
    text-align: center;
    align-items: center;
    aspect-ratio: 16 / 9;
    flex-direction: column;
    justify-content: center;
    transition: background-color .3s ease;
  }
  #cmy-verify-alert {
    font-size: 2em;
  }
  #cmy-verify-file {
    font-size: 1.5em;
  }
  #cmy-verify-input {
    display: none;
  }
</style>

<script src="/assets/js/cmy-signature-verify.js"></script>
