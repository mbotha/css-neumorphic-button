# CSS Neumorphic Button ![alt text](https://img.shields.io/badge/CSS--blue "CSS") ![alt text](https://img.shields.io/badge/HTML5--blue "CSS")
It’s a raised element made from the exact same material as the background.
 See it in action https://mbotha.github.io/css-neumorphic-button/



 
 #### Very minimal CSS
## HTML to display the button

```html
 <button type="button" class="button shadow-dark bg-dark"><i class="fa fa-play" aria-hidden="true"></i></button>
```
## CSS to generate the neumorphism

```css
.button {
    text-decoration: none;
    font-size: 16px;
    text-transform: uppercase;
    text-align: center;
    letter-spacing: .5px;
    position: relative;
    padding: 30px;
    box-sizing: border-box;
    border-radius: 12px;
    margin: 10px;
}
.bg-dark {
    background: #363a3b;
    color:#00ffdc;
}
.shadow-dark {
    border: 1px solid rgba(62, 62, 62, 0.42);
    box-shadow: 6px 6px 16px 0 rgba(0, 0, 0, 0.34), -6px -6px 26px 0 rgba(78, 78, 78, 0.98);
}
 ```
        

