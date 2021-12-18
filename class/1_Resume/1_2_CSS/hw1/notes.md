## 在html上加css
https://www.w3schools.com/css/css_howto.asp
1. `<style></style>` 在 `<head></head>` 裏面
2. `<div style="background-color:red;"></div>`
3. `<link rel="stylesheet" href="./style.css">`

## color 寫法
https://www.w3schools.com/css/css_colors.asp
1. `{color: red;}`
2. `{color: #ff0000;}`
3. `{color: #f00}` 16進位寫法 hex
4. `{color: rgb(255,0,0)}` rgb寫法
5. `{color: rgba(255,0,0,1)}` (a: 透明度) 0-255  
6. `{color:hsl(9, 100%, 64%);}` hls寫法
7. `{color:hsla(9, 100%, 64%,1);}`

## comment
https://www.w3schools.com/css/css_comments.asp

```css
/* This is a single-line comment */
p {
  color: red;
}
p {
  color: red;  /* Set text color to red */
}
```

## syntax
https://www.w3schools.com/css/css_syntax.asp
h1(selector) {
  color(property): red(value);
}
一個顏色是紅的h1

## selector
https://www.w3schools.com/css/css_selectors.asp

### element Selector

```css
p {
  text-align: center;
  color: red;
}
```

### id Selector

```css
#para1 {
  text-align: center;
  color: red;
}
```

### class Selector

```css
.center {
  text-align: center;
  color: red;
}
```

### Universal Selector

```css
* {
  text-align: center;
  color: blue;
}
```

### group selector

```css
h1, h2, p {
  text-align: center;
  color: red;
}
```

### group selector

```css
h1, h2, p {
  text-align: center;
  color: red;
}
```

### group selector

```css
h1, h2, p {
  text-align: center;
  color: red;
}
```

## 組合selector (關係)
1. 後代selector(` `): 用以選擇某個元素後代的元素（只要是直系都可）。 ex: div span 套用所有  <div> 元素內部的所有 <span> 元素。
2. 子代selector(`>`): 用以選擇某個元素後代的元素(父子)。 ex: ul > li 套用所有 <li> 元素內部的 <ul> 子元素。
3. 兄弟selector(`~`): 選擇緊接在後的所有元素，並共享父元素。。 ex: p ~ span 在p後的所有span
4. 相臨兄弟selector(`~`): 選擇緊接在後的元素，並共享父元素。。 ex: p + span 緊接在p後的span(一定要是相鄰)


### other selectors
https://www.w3schools.com/cssref/css_selectors.asp

## css 單位
1. px
2. %
3. em
4. rem
5. vw
6. vh
7. pt


## box model
https://www.w3schools.com/css/css_boxmodel.asp
寬高是從哪裡算起？
`box-sizing: border-box;` -> border以內
`box-sizing: content-box;` -> 只有content
Margin-> Border->Padding->content


## chrome devtool 開發人員工具
f12 或右鍵
https://thewayeasy.com/chrome%E9%96%8B%E7%99%BC%E8%80%85%E5%B7%A5%E5%85%B7google-devtool%E5%9F%BA%E7%A4%8E%E6%95%99%E5%AD%B8/
熟悉一下找元素 跟style & computed兩個面板
用箭頭找點擊你要的元素
responsive toggle device tool bar 去縮放畫面大小

## 常用property1
1. https://www.w3schools.com/css/css_background.asp
2. https://www.w3schools.com/css/css_border.asp
3. https://www.w3schools.com/css/css_margin.asp
4. https://www.w3schools.com/css/css_padding.asp
5. https://www.w3schools.com/css/css_dimension.asp
6. https://www.w3schools.com/css/css_outline.asp
7. https://www.w3schools.com/css/css_text.asp
8. https://www.w3schools.com/css/css_font.asp
9. https://www.w3schools.com/css/css_link.asp
10. https://www.w3schools.com/css/css_list.asp
11. https://www.w3schools.com/css/css_table.asp
12. https://www.w3schools.com/css/css_image_transparency.asp