# Div Alignment
It's on every website but stupidly fucking hard to remember

#Div Alignment

HTML:
```html
<!doctype html>
<html>
<head>
    <title>Hi, i'm harry</title>
    <link href="stylesheet.css" rel="stylesheet">
</head>
<body>
    <div class="container">
        <div class="centered-element">
          <p>vertically centered text</p>
        </div>
    </div>
    
</body>
<footer>
</footer>
</html>
```

CSS:
```css
 .container {
    display: grid;
    place-items: center;
    height: 600px;
  }

  
  .centered-element {
    margin: 0;
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
  }
  ```
