# Chapter 5: Mobile First Layout with Media Queries

In this chapter, we will learn to use media queries. We will also take a look at how to be mobile-first in CSS frameworks. Then, we will create our own layout with CSS Flexbox and CSS Grid.

## Misc. Writings

CSS Unit for responsive

In CSS, there are fixed units and flexbile units.

For example, `px` is fixed unit. And `%`, `em` are flexible units.




Laying things horizontally.


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



---

Tailwind grid util: https://tailwindgrids.com/

## Workbook Questions

What is row-column methodology in CSS layout design.

Is row or column the container?

Is row or column the items inside their container?

Can an HTML element be both child item and container at the same time?

Why min-width is mobile friendly but max-width is not?

