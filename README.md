#Bootstrap 3 for IE7 (Beta)

Bootstrap 3 drops support for Internet Explorer 7, but you can add it back by simply adding this conditional CSS.

```html
<!--[if lt IE 8]>
    <link href="/css/bootstrap-ie7.css" rel="stylesheet">
<![endif]-->
```

### Requirements
- Boostrap 3 uses the box-sizing property for layouts which is not natively supported by IE7. The polyfill 'boxsizing.htc' is REQUIRED: https://github.com/Schepp/box-sizing-polyfill


### FAQS

* Q. Do I need to make any changes to my HTML to add support for bootstrap3-ie7?
 
  A. Nope! Just include the conditional IE7 stylesheet and you're ready to go!


* Q. What about rounded corners, box shadows and gradients for IE7. How can I get those?
 
  A. I recommend CCS3Pie for adding support for those CSS3 properties to older IE. http://css3pie.com/


### Known Issues
- This is not complete yet. I'm working on fixing some issues to match the release Bootstrap 3 CSS changes.
