# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](screenshot.png)

### Built with

- HTML5
- CSS (including Flexbox)
- BEM methodology

### What I learned

-The use of the pseudo-element ::first-line to style 'Annual Plan' separate to '$59.99/year', keeping the HTML markup as simple as possible.

```css
.order-summary__cost::first-line {
    font-weight: 900;
    color: hsl(223, 47%, 23%);
}
```

-The use of aria-hidden="true" to hide decorative images from screen readers.

```html
<img class="order-summary__icon" src="images/icon-music.svg" alt="" aria-hidden="true">
```