# Animate.less - Fork from animate.css

*Just-add-water LESS animation*

`animate.less` is a bunch of cool, fun, and cross-browser animations for you to use in your projects. Great for emphasis, home pages, sliders, and general just-add-water-awesomeness.

## Why?

`animate.css` is a great tool but like other css libraries you only use a little part of the code.

This way you will only use what you need, making the css much much smaller.

I'm also lazy for compile code and I don't use sass.

Finally, I want to clarify that all the credit of this work belongs to [animate.css] (http://daneden.github.io/animate.css/) and this is just a personal project, but feel free to use it.

## Basic Usage

1. import `animate.less` in your less file.

```less
  @import "https://raw.githubusercontent.com/Mayccoll/animate.less/master/animate.less";
```

2. Add the class `animated` to the element you want to animate.
 You may also want to include the class `infinite` for an infinite loop.
 And finally include the animation you want.

`main.less`

```less
  .myClass {
    .animated;
    .infinite;
    .bounce;
  }
```

`index.html`

```html
<h1 class="myClass">Example 1</h1>

```

Note: I remove the webkit prefixes because i assume you're less compiler will add them for you.

-  **you can define the animations you will use.**

`main.less`

```less
  .bounce {
    .animated;
    .bounce;
  }
```

`index.html`

```html
<h2 class="bounce">Example 1</h1>
<h2 class="bounce">Example 1</h1>

```

**More examples:** http://codepen.io/mayccoll/pen/XbRMRB

### You can add the following classes:

  * `bounce`
  * `flash`
  * `pulse`
  * `rubberBand`
  * `shake`
  * `swing`
  * `tada`
  * `wobble`
  * `jello`
  * `bounceIn`
  * `bounceInDown`
  * `bounceInLeft`
  * `bounceInRight`
  * `bounceInUp`
  * `bounceOut`
  * `bounceOutDown`
  * `bounceOutLeft`
  * `bounceOutRight`
  * `bounceOutUp`
  * `fadeIn`
  * `fadeInDown`
  * `fadeInDownBig`
  * `fadeInLeft`
  * `fadeInLeftBig`
  * `fadeInRight`
  * `fadeInRightBig`
  * `fadeInUp`
  * `fadeInUpBig`
  * `fadeOut`
  * `fadeOutDown`
  * `fadeOutDownBig`
  * `fadeOutLeft`
  * `fadeOutLeftBig`
  * `fadeOutRight`
  * `fadeOutRightBig`
  * `fadeOutUp`
  * `fadeOutUpBig`
  * `flipInX`
  * `flipInY`
  * `flipOutX`
  * `flipOutY`
  * `lightSpeedIn`
  * `lightSpeedOut`
  * `rotateIn`
  * `rotateInDownLeft`
  * `rotateInDownRight`
  * `rotateInUpLeft`
  * `rotateInUpRight`
  * `rotateOut`
  * `rotateOutDownLeft`
  * `rotateOutDownRight`
  * `rotateOutUpLeft`
  * `rotateOutUpRight`
  * `hinge`
  * `rollIn`
  * `rollOut`
  * `zoomIn`
  * `zoomInDown`
  * `zoomInLeft`
  * `zoomInRight`
  * `zoomInUp`
  * `zoomOut`
  * `zoomOutDown`
  * `zoomOutLeft`
  * `zoomOutRight`
  * `zoomOutUp`
  * `slideInDown`
  * `slideInLeft`
  * `slideInRight`
  * `slideInUp`
  * `slideOutDown`
  * `slideOutLeft`
  * `slideOutRight`
  * `slideOutUp`



## With javascript.


First you need to define the classes you what to use in your less file.

```less
  .zoomIn {
    .animated;
    .zoomIn;
  }
```


You can do a whole bunch of other stuff with animate.css when you combine it with jQuery or add your own CSS rules. Dynamically add animations using jQuery with ease:

```javascript
$('#yourElement').addClass('animated zoomIn');
```

The rest of the documentation can be found at: http://daneden.github.io/animate.css/

## License
Animate.css is licensed under the MIT license. (http://opensource.org/licenses/MIT)
