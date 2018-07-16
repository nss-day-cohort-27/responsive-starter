# Bootstrap - Line Up Those Images

### Bootstrap Website Details
* http://getbootstrap.com/
* Get started with CDN links: https://getbootstrap.com/docs/4.0/getting-started/introduction/
* Checkout examples: https://getbootstrap.com/docs/4.0/examples/
* Starter Template: https://getbootstrap.com/docs/4.0/examples/starter-template/

Bootstrap requires a containing element to wrap site contents and house the grid system.

**Fixed Width**
```
<div class="container">
  ...
</div>
```

**or Full Width: spanning the entire width of the viewport**
```
<div class="container-fluid">
  ...
</div>
```


### Mobile First
Disables zooming on mobile devices
```
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
```


### The Grid
* https://getbootstrap.com/docs/4.0/layout/grid/
* Media Queries - based on different size viewports.
* Rows are made up of 12 columns.
* Divide 12 by the number of visible columns (any combination adding up to 12).
```
<div class="row">
    <div class="col-lg-4">Column 1</div>
    <div class="col-lg-4">Column 2</div>
    <div class="col-lg-4">Column 3</div>
</div>
```
* OR use a unit-less value and let Bootstrap figure out the rest
```
<div class="row">
    <div class="col">Column 1</div>
    <div class="col">Column 2</div>
    <div class="col-4">Column 3</div>
</div>
```

* Columns have additional classes related to size: xl, lg, md, sm.
    - **xl** Resizes as soon as the browser window reduces below 1200px
    - **lg** Resizes as soon as the browser window reduces below 992px
    - **md** Resizes as soon as the browser window reduces below 768px
    - **sm** Resizes as soon as the browser window reduces below 575px
    - **col/xs** No resize


### Images
* `.img-fluid` class applies:
    - max-width: 100%;
    - height: auto;
    - to the image so that it scales nicely to the parent element
* Align images with float classes or text alignment classes
    - `.float-left` or `.float-right` or `mx-auto`
    - `.text-center`
    - https://getbootstrap.com/docs/4.0/content/images/

### Grid Detail Example
* https://github.com/brendalong/responsive-starter

### Read Bootstrap docs for more options including Typography
* https://getbootstrap.com/docs/4.0/content/typography/

## Practice
### Using Bootstrap, create the homepage for the Zoo
Include the following details:
* Navbar with Logo(text) and links to three areas of the zoo.
* Feature 3 animals with image, title, copy
* Include a footer with additional links to other zoos.
* Article about the new area, conservation details, or events.
   * Try out a button group
   * Try out a form inputs.

