# sass-mixins
Sass Mixins Library

**Mixins**

* [`box-sizing`](#box-sizing)
* [`transition`]
* [`translateY`]
* [`user-select`]

**Flex Mixins**

* [`align-items`]
* [`inline-flex`]
* [`justify-content`]


### box-sizing
```scss
@include box-sizing($value)
```

```scss
@mixin box-sizing($value) {
  -webkit-box-sizing: $value;
  -moz-box-sizing: $value;
  box-sizing: $value;
}
```
