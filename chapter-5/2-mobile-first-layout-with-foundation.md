# Mobile-first layout with foundation

Foundation is a robust mobile-first CSS framework. It supported mobile from version 1 and had a mobile grid since version 2.

https://replit.com/@makzan/Foundation-Example-1

## Including Foundation from CDN

```html
<!-- Compressed CSS -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/foundation-sites@6.6.3/dist/css/foundation.min.css" integrity="sha256-ogmFxjqiTMnZhxCqVmcqTvjfe1Y/ec4WaRj/aQPvn+I=" crossorigin="anonymous">

<!-- foundation-float.min.css: Compressed CSS with legacy Float Grid -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/foundation-sites@6.6.3/dist/css/foundation-float.min.css" integrity="sha256-4ldVyEvC86/kae2IBWw+eJrTiwNEbUUTmN0zkP4luL4=" crossorigin="anonymous">
```

## Example of using Foundation’s row and column

```html
<div class="row">
  <div class="column">
    12
  </div>
</div>

<div class="row">
  <div class="medium-6 columns">6</div>
  <div class="medium-6 columns">6</div>
</div>

<div class="row">
  <div class="medium-4 columns">4</div>
  <div class="medium-4 columns">4</div>
  <div class="medium-4 columns">4</div>
</div>

<div class="row">
  <div class="small-6 medium-3 columns">3</div>
  <div class="small-6 medium-3 columns">3</div>
  <div class="small-6 medium-3 columns">3</div>
  <div class="small-6 medium-3 columns">3</div>
</div>
```

## Full example


```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="style.css" rel="stylesheet" type="text/css" />

    <!-- Compressed CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/foundation-sites@6.6.3/dist/css/foundation.min.css" integrity="sha256-ogmFxjqiTMnZhxCqVmcqTvjfe1Y/ec4WaRj/aQPvn+I=" crossorigin="anonymous">

    <!-- foundation-float.min.css: Compressed CSS with legacy Float Grid -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/foundation-sites@6.6.3/dist/css/foundation-float.min.css" integrity="sha256-4ldVyEvC86/kae2IBWw+eJrTiwNEbUUTmN0zkP4luL4=" crossorigin="anonymous">

    <style>
      /* Debug */
      .row {
        margin: 1em;
      }
      .column, .columns {
        border: 1px solid grey;
      }
    </style>

  </head>
  <body>
    
    <div class="row">
      <div class="column">
        12
      </div>
    </div>

    <div class="row">
      <div class="medium-6 columns">6</div>
      <div class="medium-6 columns">6</div>
    </div>

    <div class="row">
      <div class="medium-4 columns">4</div>
      <div class="medium-4 columns">4</div>
      <div class="medium-4 columns">4</div>
    </div>

    <div class="row">
      <div class="small-6 medium-3 columns">3</div>
      <div class="small-6 medium-3 columns">3</div>
      <div class="small-6 medium-3 columns">3</div>
      <div class="small-6 medium-3 columns">3</div>
    </div>

    <div class="row">
      <div class="small-6 medium-1 columns">1</div>
      <div class="small-6 medium-1 columns">1</div>
      <div class="small-6 medium-1 columns">1</div>
      <div class="small-6 medium-1 columns">1</div>
      <div class="small-6 medium-1 columns">1</div>
      <div class="small-6 medium-1 columns">1</div>
      <div class="small-6 medium-1 columns">1</div>
      <div class="small-6 medium-1 columns">1</div>
      <div class="small-6 medium-1 columns">1</div>
      <div class="small-6 medium-1 columns">1</div>
      <div class="small-6 medium-1 columns">1</div>
      <div class="small-6 medium-1 columns">1</div>
    </div>

    <script src="script.js"></script>
  </body>
</html>
```