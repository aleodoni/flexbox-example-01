# FlexBox Training

## Setting Embed Font

```html
<link href="https://fonts.googleapis.com/css?family=Roboto:400,500&display=swap" rel="stylesheet">
```

## Reseting HTML tags

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background: #e6ecf0;
  font-family: 'Roboto', sans-serif;
  text-rendering: optimizeLegibility !important;
  -webkit-font-smoothing: antialiased !important;
}

input, button {
  outline: 0;
}

.content {
  max-width: 1100px;
  margin: 0 auto;
}
```