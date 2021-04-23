# Introducing Media Queries

Media queries give us alternative 

For example, given that we have the following HTML.

```html
<div class="container">
  <header>
    Header: Media queries basic, with float.        
  </header>
  <main>
    <h1>Main content here.</h1>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Distinctio quaerat animi architecto, fuga hic at nulla, omnis nostrum neque assumenda cum officiis repudiandae, odio impedit et beatae accusamus dignissimos illum?</p>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Distinctio quaerat animi architecto, fuga hic at nulla, omnis nostrum neque assumenda cum officiis repudiandae, odio impedit et beatae accusamus dignissimos illum?</p>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Distinctio quaerat animi architecto, fuga hic at nulla, omnis nostrum neque assumenda cum officiis repudiandae, odio impedit et beatae accusamus dignissimos illum?</p>
  </main>
</div>
<footer>
  Footer goes here.
</footer>
```

By default, the block elements are 100% width and things are listed from top to bottom. This fits the mobile scrolling practice.

When we want to align the elements horizontally when the screen becomes wider, we can use `@media screen` media query and define a minimal width to apply the additional CSS styles.

```css
*{box-sizing: border-box}

@media screen and (min-width: 600px) {
  .container {
    overflow: auto;
  }

  header {
    float: left;
    width: 20%;
  }
  main {
    float: left;
    width: 80%;
  }
}
```

## Box sizing

Box-sizing: Border-box vs content-box

Demo:

https://codepen.io/makzan/pen/VwPBWPP

Box sizing defines what we meant when setting the dimension of an element. If it is `content-box`, we are setting the dimension of the content. The padding value and border width are expanded in addition to the size we set.

If it is `border-box`, we are setting the dimension of the entire element, including the content, padding and the border.

The `content-box` option is obviously more difficult to control. This was not a problem until we define layout by using ratio percentages instead of fixed dimensions. When we set 50% width to an element, we want it to be exactly half of the container.

That’s why in modern web development, we always apply `box-sizing: border-box` to our layout.

```css
*{box-sizing: border-box}
```



## Responsive with Flexbox

```css
@media screen and (min-width: 600px) {
  .container {
    display: flex;
  }

  header {
    flex: 0 1 200px;
  }
  main {
    flex: 1;
  }
}
```

## Responsive with Grid

```css
@media screen and (min-width: 600px) {
  .container {
    display: grid;
    grid-template-columns: 200px auto;
  }

}
```