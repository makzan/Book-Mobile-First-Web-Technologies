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