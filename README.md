# List Object #

The list object is responsible for creating inline, block and span lists.


### Installation ###

```
npm install --save iotacss-list
```


### Dependencies ###

* [Settings.Default](https://github.com/iotacss/settings.default)


### Options ###

```
$iota-list--block         : false !default;
$iota-list--inline        : false !default;
$iota-list--span          : false !default;  // The list elements are inline and they take the 100% of their container
$iota-list-gutter-default : 10px !default;
$iota-list-gutter-extra   : () !default;
```


### Classes ###

```
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
