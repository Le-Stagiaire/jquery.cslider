# jquery.cslider

A simple parallax content slider with different animations for each slider element and a background parallax effect.

http://tympanus.net/codrops/2012/03/15/parallax-content-slider-with-css3-and-jquery/

# Usage examples

```javascript
$('#da-slider').cslider({
  current : 0, // index of current slide
  bgincrement: 50, // background position (parallax effect) when sliding
  autoplay: false, // slideshow on / off
  interval: 4000 // time between transitions
});
```

# Changes

This "[delegator][1] version" of `jquery.cslider` is largely backwards-compatible with the original,
except for the following notable differences:

### In the spirit of shaming old browsers:
 - Modernizr removed
 - Vendor-prefixed and non-standard CSS rules removed

### Moving JavaScript into the future:
 - `jquery.cslider` plugin is now CommonJS-compatible
 - package.json added for `npm` usability

# License

For the full text of the [Codrops][2] license, please see [LICENSE][3].

# Disclaimer

We have placed our modifications of this original resource on GitHub in good faith, with the intention of promoting code reusability and the use of the `npm` package manager. :smile:

[1]: https://www.delegator.com/
[2]: http://tympanus.net/codrops/
[3]: ./LICENSE
