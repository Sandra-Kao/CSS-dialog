# CSS-dialog

Please see Codepen:

https://codepen.io/K-SY/pen/gOmwdqE

![image](https://user-images.githubusercontent.com/63223781/118790055-fc8c7c00-b8c7-11eb-8fab-613e81606a95.png)


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
