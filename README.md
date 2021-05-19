# CSS-dialog

Please see Codepen:

https://codepen.io/K-SY/pen/gOmwdqE

### HTML

``` html
<section class="dialog">
  <h3 class="title">Say Hi,</h3>
  <p class="description">
    I am HERE for help ...
  </p>
</section>

```

### CSS
```css
.dialog {
    padding: 30px;
    background-color: pink;
    width:20%;
    position: relative;
    border-radius: 10px;
}

     .dialog::after {
        content: '';
        border-right: 20px solid transparent;
        border-left: 20px solid transparent;
        border-top: 20px solid pink;
        position: absolute;
        bottom: -20px;
        left: calc((100% - 40px) / 2);
    }
```
