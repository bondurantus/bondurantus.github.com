# bondurantus

## How to add to the site:

The navigation happens automatically based on what's on the page.

An image is of the following format, a containing `<div>` with `class="image"` and then an `img` tag of the source of the image file and finally a `<div>` with `class="caption"` with whatever the caption is.

```html
  <div class="image">
    <img src="http://farm6.staticflickr.com/5129/5321773529_a08eaa1b75_z.jpg">
    <div class="caption">ADVICE BOX. Burned wood, 2010.</div>
  </div>
```

The page overall looks like so, if all instances of an image are removed:

```html
<div id="main">
  <div id="left">
    <div class="images">
      <!-- images go here -->
    </div>
  </div>

  <div id="right">
    <div class="images">
      <!-- images go here -->
    </div>
  </div>
</div>
```

Where you see the comments is where to place the 'image' markup from above. The order of the images is from top to bottom.