# 製作背景冒泡的動畫

## 使用到的 css 功能

-   :nth-child(even / odd / 3n+0)

-   keyframes 動畫製作，包含屬性有哪些
-   transform 、 transition、animation 的差別與用法
-   原生 CSS 變數運用技巧（CSS Variables）
    -   [延伸文章閱讀](https://w3c.hexschool.com/blog/21985acb)
    -   這裡作者是直接在 html 裡面設定 style，並給予自訂屬定--1:(秒數)，然後在到 css 檔案中拿取出來 var(--i)，計算 animation-duration 的時間
    -   再來一個範例

```javascript=
<p style="--clr:red;">RED</p>
<p style="--clr:yellow;">YELLOW</p>
<p style="--clr:green">GREEN</p>

<style>
    p {
        color: var(--clr);
    }
</style>

就會有相對應的顏色，不然一班都是在css 頂部設定:root{}，裡面再放進我們要的自訂一屬性
```
