---
title: "HTML 斷行 段落 格式化"
draft: false
images:
series: 
series_order: 1
tags:
    - HTML
    - 斷行
    - 段落
    - 格式化
---
<font color = "#48d1cc">

>## 一、br 斷行 p 段落

瀏覽器不能用Enter斷行，</br>
只能用`<br>`做斷行</br>
`<p></p>` 可以分段，會自動空格

```html 
    <p>
        AI驅動產業升級，全球瘋搶人才，
        <br>AI工程師年薪上看150~200萬！
        生成式AI浪潮來襲！把握進修好時機，
        <hr color="#844200" width="50%" align="left">
        <br>AI整合應用奪先機。
        <br>精選六大領域課程：
        <br>程式、影音、平面、插畫、遊戲、室內設計，
        <br>資深業師乾貨不藏私，打造全領域 AI通才。
        <hr color="#blue" width="50%" align="left">
        <br>利用Python串接OpenAI，學習語法與應用，
        <br>輔助開發者編寫和生成程式碼。
        <br>從基礎到進階，全面解析Python應用，
        <br>成為<b><i><u>AI人工智慧工程師</u></i></b>的第一步。
        <hr color="#blue" width="50%" align="left">
    </p>
```

---
## pre 格式化

格式化內容，在裡面是甚麼樣子網頁就是甚麼樣子

```html
<pre>
AI驅動產業升級，全球瘋搶人才，
AI工程師年薪上看150~200萬！
生成式AI浪潮來襲！把握進修好時機，
<hr color="#844200" width="50%" align="left">
AI整合應用奪先機。
精選六大領域課程：
程式、影音、平面、插畫、遊戲、室內設計，
資深業師乾貨不藏私，打造全領域 AI通才。
<hr color="#blue" width="50%" align="left">
利用Python串接OpenAI，學習語法與應用，
輔助開發者編寫和生成程式碼。
從基礎到進階，全面解析Python應用，
成為<b><i><u>AI人工智慧工程師</u></i></b>的第一步。
<hr color="#blue" width="50%" align="left">
</pre>
```