# List Object #

The list object is responsible for creating inline, block and span lists.


### Installation ###

```
npm install --save iotacss-obj-list
```


### Options ###

```sass
$iota-obj-list-namespace      : 'list' !default;
$iota-obj-list-item-name      : 'item' !default;
$iota-obj-list-block-name     : 'block' !default;
$iota-obj-list-inline-name    : 'inline' !default;
$iota-obj-list-span-name      : 'span' !default;

$iota-obj-list-gutter-default : $iota-global-gutter-default !default;
$iota-obj-list-gutter-extra   : () !default;

$iota-obj-list-block          : false !default;
$iota-obj-list-inline         : false !default;
$iota-obj-list-span           : false !default;
```


### Classes ###

```sass
.o-list
  .o-list__item


// Modifiers

.o-list--block
.o-list--inline
.o-list--span


// Extra gutter sizes

$iota-list-gutter-extra   : (
  small: 5px;
  large: 20px;
);

.o-list--small
.o-list--large
```
