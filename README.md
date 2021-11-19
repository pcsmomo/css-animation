# css-animation

Creative Advanced CSS Animations - Create 100 Projects! by Ahmed Sadek

## Details

<details>
  <summary>Click to Contract/Expend</summary>

### 5. what properties can be transitioned ?

[MDN - Animatable CSS properties](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animated_properties)

### 9. CSS rotate function

```css
img:hover {
  transform: rotate(1turn); /* 360deg */
  transform: rotate(-0.5turn); /* -180deg */
  transform: rotate(200grad); /* 180deg */
}
```

### 11. transform origin

```css
a {
  transform-origin: 20% 80%;
}
```

### 27. creative button hover effect

```css
a {
  mix-blend-mode: multiply;
  transform: perspective(1000px) rotateX(75deg);
}
```

### 67. creative layered card hover effect

```css
img {
  object-fit: cover;
}
```

```css
div {
  animation-fill-mode: both; /* none | forwards | backwords | both */
}
```

### 83. driving a car and a motor bike using css animation

[freepik - free images](https://www.freepik.com/)

### 113. what is the CSS clip path property and how we can use it o create shapes

[Clippy - Clip path polygon](https://bennettfeely.com/clippy/)

### 118. black to white and white to black text effect using CSS clip path

if

```css
/* if the number of vertexes are different, trasition won't work */
h1:nth-child(2) {
  transition: all 0.5s;
  /* clip-path: polygon(0 0, 100% 0, 100% 0); */
  clip-path: polygon(0 0, 100% 0, 100% 0, 0% 100%);
}

h1:nth-child(2):hover {
  clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
}
```

</details>
