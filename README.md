<h1>JS.Smooth Loading</h1>
<p>
    Image loading method with a bit of jQuery. Should be easy enough to convert to a non-API dependent method.
</p>

<h2>How it works</h2>
<p>
    Takes advantage of how the browser loads images by creating a placeholder image then after-the-fact
    appending the actual image from a "data-src" attribute.
</p>
<p>
    This particular bit of JavaScript works in conjunction with the classes "opacity" and "fadein".
</p>

<h2>Browser compatibility</h2>
<p>
    Tested in Firefox, Chrome, Opera, and IE flavors 7-9. IE 7 and 8 will simply have the images "magically" appear.
</p>

<h2>License</h2>
<p>
    I feel weird about this since this pattern has got to be out there. But my aspect is released under the
    <a href="http://opensource.org/licenses/mit-license.php">MIT License</a>.
</p>
<p>
    I did include <a href="http://necolas.github.com/normalize.css">Normalize.css</a> and the box model tweak from
    <a href="http://www.paulirish.com/2012/box-sizing-border-box-ftw/">Paul Irish</a> for general demo formatting purposes.
</p>
