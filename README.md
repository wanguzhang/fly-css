# fly-css
css 3 学习整理

## css 揭秘
```txt
em/rem
vw、 vh、 vmin 和 vmax
calc()
color()
```
```css
conic-gradient
radial-gradient
linear-gradient
background-size
background-position

```
## calc()

```css
calc(100% - 20px)
```
## background

### background-clip
```txt
background-clip: padding-box; // 裁剪背景色，不蔓延到 border
background-clip: border-box;
```

## position

#### position-relative

```js
不会改变别的文档流位置
```

### position-absolute

```js
当前脱离文档流
```

### box-sizing

```txt
content width + padding + border = 实际盒子大小
content height + padding + border = 实际盒子大小

设置盒子的大小是否可以被 padding 和 border 影响。

border-box 会将 content box + border + padding 自适应为 width height
```