Helpful Sass Mixins
=================================

A collection of useful plug and play mixins for the [Sass Language](http://sass-lang.com/) from the [PRPL](http://www.prpl.rs/) Dev team.

Just include the file into your project:
```css
@import "sass-mixins";
```

Examples
----------------------------------

Absolute position
```css
@include abs-pos(20px, 30px, auto, auto)
```

Full page fixed background
```css
@include background-cover('path/to/file.jpg')
```

Border-box Sizing (More Info: http://bit.ly/10kDnEz)
```css
@include border-box()
```

Element Shadow
```css
@include box-shadow(5px, 5px, 5px, #000)
```

Media Query
```css
@include break-min('min-width: 321px'){
	/* Custom CSS Styles */
}
```

Media Query (Max-Width)
```css
@include break-max(700px) {
	/* Custom CSS Styles */
}
```

Media Query (Min-Width)
```css
@include break-min(700px) {
	/* Custom CSS Styles */
}
```

Clear Floats (More Info: http://bit.ly/evOPw5)
```css
@include clearfix()
```

REM Font Sizing (More Info: http://bit.ly/IhXzmm)
```css
@include hide-text()
```

Text Replacement (More Info: http://bit.ly/Asq62d)
```css
@include hide-text()
```

Retina Images
```css
@include image-2x('path/to/file.jpg', 500px, 500px)
```

Removes list stylings
```css
@include list-reset()
```

CSS3 Linear Gradient (with IE support and fallback)
```css
@include linear-gradient(#ffffff, #000000) 
```

Disables Text Selection on Element
```css
@include no-text-select()
```

Opacity
```css
@include opacity(0)
```

CSS3 Rounded Corners
```css
@include rounded-corners(10px)
```

CSS3 Animation Transition
```css
@include transition('background-color 3s linear 1s')
```
