


```css
/* # fr实现等分响应式

## fr 等分单位，可以将容器的可用空间分成想要的多个等分空间。利用这个特性，我们能够轻易实现一个等分响应式。grid-template-columns: 1fr 1fr 1fr 表示容器分为三等分 */
.container {
    margin: 50px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-gap:10px 20px;
    grid-auto-rows:50px;
}
```