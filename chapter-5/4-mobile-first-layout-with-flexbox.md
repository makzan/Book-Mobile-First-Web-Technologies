
https://replit.com/@makzan/Responsive-Web-Example-2-Flexbox

```css
/* Border box */
* {
  box-sizing: border-box;
}

img {
  max-width: 100%;
}

/* Grid */
.row {
  /* if you need a largest width */
  width: 1920px;
  max-width: 100%;
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
}

.row .row {
  margin-left: -10px;
  margin-right: -10px;
  width: auto;
  max-width: none;
}

.col {
  padding: 0 10px;
  min-width: 0;
  border: 1px dashed LIGHTGRAY;
}

@media screen and (min-width: 0) {
  .small-vertical {
    flex-direction: column;
  }

  .small-horizontal {
    flex-direction: row;
  }

  .small-hidden {
    display: none;
  }

  .small-auto {
    display: block;
    flex: 1;
  }

  .small-shrink {
    display: block;
    flex: 0 1 auto;
  }

  .small-1 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 1 );
  }

  .small-2 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 2 );
  }

  .small-3 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 3 );
  }

  .small-4 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 4 );
  }

  .small-5 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 5 );
  }

  .small-6 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 6 );
  }

  .small-7 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 7 );
  }

  .small-8 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 8 );
  }

  .small-9 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 9 );
  }

  .small-10 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 10 );
  }

  .small-11 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 11 );
  }

  .small-12 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 12 );
  }
}
@media screen and (min-width: 500px) {
  .medium-vertical {
    flex-direction: column;
  }

  .medium-horizontal {
    flex-direction: row;
  }

  .medium-hidden {
    display: none;
  }

  .medium-auto {
    display: block;
    flex: 1;
  }

  .medium-shrink {
    display: block;
    flex: 0 1 auto;
  }

  .medium-1 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 1 );
  }

  .medium-2 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 2 );
  }

  .medium-3 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 3 );
  }

  .medium-4 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 4 );
  }

  .medium-5 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 5 );
  }

  .medium-6 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 6 );
  }

  .medium-7 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 7 );
  }

  .medium-8 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 8 );
  }

  .medium-9 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 9 );
  }

  .medium-10 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 10 );
  }

  .medium-11 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 11 );
  }

  .medium-12 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 12 );
  }
}
@media screen and (min-width: 1000px) {
  .large-vertical {
    flex-direction: column;
  }

  .large-horizontal {
    flex-direction: row;
  }

  .large-hidden {
    display: none;
  }

  .large-auto {
    display: block;
    flex: 1;
  }

  .large-shrink {
    display: block;
    flex: 0 1 auto;
  }

  .large-1 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 1 );
  }

  .large-2 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 2 );
  }

  .large-3 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 3 );
  }

  .large-4 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 4 );
  }

  .large-5 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 5 );
  }

  .large-6 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 6 );
  }

  .large-7 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 7 );
  }

  .large-8 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 8 );
  }

  .large-9 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 9 );
  }

  .large-10 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 10 );
  }

  .large-11 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 11 );
  }

  .large-12 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 12 );
  }
}
@media screen and (min-width: 1200px) {
  .xlarge-vertical {
    flex-direction: column;
  }

  .xlarge-horizontal {
    flex-direction: row;
  }

  .xlarge-hidden {
    display: none;
  }

  .xlarge-auto {
    display: block;
    flex: 1;
  }

  .xlarge-shrink {
    display: block;
    flex: 0 1 auto;
  }

  .xlarge-1 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 1 );
  }

  .xlarge-2 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 2 );
  }

  .xlarge-3 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 3 );
  }

  .xlarge-4 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 4 );
  }

  .xlarge-5 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 5 );
  }

  .xlarge-6 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 6 );
  }

  .xlarge-7 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 7 );
  }

  .xlarge-8 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 8 );
  }

  .xlarge-9 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 9 );
  }

  .xlarge-10 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 10 );
  }

  .xlarge-11 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 11 );
  }

  .xlarge-12 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 12 );
  }
}
@media screen and (min-width: 1600px) {
  .xxlarge-vertical {
    flex-direction: column;
  }

  .xxlarge-horizontal {
    flex-direction: row;
  }

  .xxlarge-hidden {
    display: none;
  }

  .xxlarge-auto {
    display: block;
    flex: 1;
  }

  .xxlarge-shrink {
    display: block;
    flex: 0 1 auto;
  }

  .xxlarge-1 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 1 );
  }

  .xxlarge-2 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 2 );
  }

  .xxlarge-3 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 3 );
  }

  .xxlarge-4 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 4 );
  }

  .xxlarge-5 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 5 );
  }

  .xxlarge-6 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 6 );
  }

  .xxlarge-7 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 7 );
  }

  .xxlarge-8 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 8 );
  }

  .xxlarge-9 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 9 );
  }

  .xxlarge-10 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 10 );
  }

  .xxlarge-11 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 11 );
  }

  .xxlarge-12 {
    display: block;
    flex: 0 1 calc( 100% / 12 * 12 );
  }
}
/* Block grid */
.block-grid {
  display: flex;
  flex-wrap: wrap;
}

.block-grid > * {
  flex: 1;
}

@media screen and (min-width: 0) {
  .block-grid.small-up-to-2 > * {
    flex: 0 1 calc( 100% / 2 );
  }

  .block-grid.small-up-to-3 > * {
    flex: 0 1 calc( 100% / 3 );
  }

  .block-grid.small-up-to-4 > * {
    flex: 0 1 calc( 100% / 4 );
  }

  .block-grid.small-up-to-5 > * {
    flex: 0 1 calc( 100% / 5 );
  }

  .block-grid.small-up-to-6 > * {
    flex: 0 1 calc( 100% / 6 );
  }

  .block-grid.small-up-to-7 > * {
    flex: 0 1 calc( 100% / 7 );
  }

  .block-grid.small-up-to-8 > * {
    flex: 0 1 calc( 100% / 8 );
  }

  .block-grid.small-up-to-9 > * {
    flex: 0 1 calc( 100% / 9 );
  }

  .block-grid.small-up-to-10 > * {
    flex: 0 1 calc( 100% / 10 );
  }
}
@media screen and (min-width: 500px) {
  .block-grid.medium-up-to-2 > * {
    flex: 0 1 calc( 100% / 2 );
  }

  .block-grid.medium-up-to-3 > * {
    flex: 0 1 calc( 100% / 3 );
  }

  .block-grid.medium-up-to-4 > * {
    flex: 0 1 calc( 100% / 4 );
  }

  .block-grid.medium-up-to-5 > * {
    flex: 0 1 calc( 100% / 5 );
  }

  .block-grid.medium-up-to-6 > * {
    flex: 0 1 calc( 100% / 6 );
  }

  .block-grid.medium-up-to-7 > * {
    flex: 0 1 calc( 100% / 7 );
  }

  .block-grid.medium-up-to-8 > * {
    flex: 0 1 calc( 100% / 8 );
  }

  .block-grid.medium-up-to-9 > * {
    flex: 0 1 calc( 100% / 9 );
  }

  .block-grid.medium-up-to-10 > * {
    flex: 0 1 calc( 100% / 10 );
  }
}
@media screen and (min-width: 1000px) {
  .block-grid.large-up-to-2 > * {
    flex: 0 1 calc( 100% / 2 );
  }

  .block-grid.large-up-to-3 > * {
    flex: 0 1 calc( 100% / 3 );
  }

  .block-grid.large-up-to-4 > * {
    flex: 0 1 calc( 100% / 4 );
  }

  .block-grid.large-up-to-5 > * {
    flex: 0 1 calc( 100% / 5 );
  }

  .block-grid.large-up-to-6 > * {
    flex: 0 1 calc( 100% / 6 );
  }

  .block-grid.large-up-to-7 > * {
    flex: 0 1 calc( 100% / 7 );
  }

  .block-grid.large-up-to-8 > * {
    flex: 0 1 calc( 100% / 8 );
  }

  .block-grid.large-up-to-9 > * {
    flex: 0 1 calc( 100% / 9 );
  }

  .block-grid.large-up-to-10 > * {
    flex: 0 1 calc( 100% / 10 );
  }
}
@media screen and (min-width: 1200px) {
  .block-grid.xlarge-up-to-2 > * {
    flex: 0 1 calc( 100% / 2 );
  }

  .block-grid.xlarge-up-to-3 > * {
    flex: 0 1 calc( 100% / 3 );
  }

  .block-grid.xlarge-up-to-4 > * {
    flex: 0 1 calc( 100% / 4 );
  }

  .block-grid.xlarge-up-to-5 > * {
    flex: 0 1 calc( 100% / 5 );
  }

  .block-grid.xlarge-up-to-6 > * {
    flex: 0 1 calc( 100% / 6 );
  }

  .block-grid.xlarge-up-to-7 > * {
    flex: 0 1 calc( 100% / 7 );
  }

  .block-grid.xlarge-up-to-8 > * {
    flex: 0 1 calc( 100% / 8 );
  }

  .block-grid.xlarge-up-to-9 > * {
    flex: 0 1 calc( 100% / 9 );
  }

  .block-grid.xlarge-up-to-10 > * {
    flex: 0 1 calc( 100% / 10 );
  }
}
@media screen and (min-width: 1600px) {
  .block-grid.xxlarge-up-to-2 > * {
    flex: 0 1 calc( 100% / 2 );
  }

  .block-grid.xxlarge-up-to-3 > * {
    flex: 0 1 calc( 100% / 3 );
  }

  .block-grid.xxlarge-up-to-4 > * {
    flex: 0 1 calc( 100% / 4 );
  }

  .block-grid.xxlarge-up-to-5 > * {
    flex: 0 1 calc( 100% / 5 );
  }

  .block-grid.xxlarge-up-to-6 > * {
    flex: 0 1 calc( 100% / 6 );
  }

  .block-grid.xxlarge-up-to-7 > * {
    flex: 0 1 calc( 100% / 7 );
  }

  .block-grid.xxlarge-up-to-8 > * {
    flex: 0 1 calc( 100% / 8 );
  }

  .block-grid.xxlarge-up-to-9 > * {
    flex: 0 1 calc( 100% / 9 );
  }

  .block-grid.xxlarge-up-to-10 > * {
    flex: 0 1 calc( 100% / 10 );
  }
}
```
