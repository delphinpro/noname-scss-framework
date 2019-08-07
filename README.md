# Scss framework

A set of mixins

## Install
 
```
npm install noname-scss-framework
```

## Usage

```scss
@import "node_modules/noname-scss-framework/framework";
```

```scss
/*==
 *== Init styles
 *== ======================================= ==*/

@include nn-box-model(border-box);
@include nn-reboot();

/*==
 *== SVG icons
 *== ======================================= ==*/

.i {
  @include nn-svg-symbol-icon-base();
}

/*==
 *== Animations
 *== ======================================= ==*/

@include nn-strip-gradient-animation();

/*==
 *== Not loaded images
 *== ======================================= ==*/

@include nn-mark-not-loaded-images();
```

## Mixins
