---
title: "HTML 有序清單"
draft: false
images:
series: 
series_order: 1
tags:
    - HTML
    - 清單
---

<font color = "#48d1cc">

## 一、標籤

```html
<ol></ol> 清單起始和結束
```

---
## 二、內容

```html
<li></li> 清單選項
```

---
## 三、屬性 

### 1. 控制清單之前數字的參數顯示成A. B. C......

```html
<ol type="A">
    <li>data 1</li>
    <li>data 2</li>
    <li>data 3</li>
</ol>
```

### 2. 控制清單之前數字的參數顯示成a. b. c......

```html
<ol type="a">
    <li>data 1</li>
    <li>data 2</li>
    <li>data 3</li>
</ol>
```

### 3. 控制清單之前數字的參數顯示成I. II. III......

```html
<ol type="A">
    <li>data 1</li>
    <li type="l">data 2</li>
    <li>data 3</li>
</ol>
```

### 4. 控制清單之前數字的參數顯示成i. i. iii......

```html
<ol type="A">
    <li>data 1</li>
    <li type="i">data 2</li>
    <li>data 3</li>
</ol>
```

### 5. 預設設置，控制清單之前數字的參數顯示成1. 2. 3......

```html
<ol type="A">
    <li type="1">data 1</li>
    <li type="1">data 2</li>
    <li type="1">data 3</li>
</ol>
```

### 6. 起始的數值

```html
<ol type="A" star="3">
    <li type="1">data 1</li>
    <li type="1">data 2</li>
    <li type="1">data 3</li>
</ol>
```