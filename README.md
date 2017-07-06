# sass-mixins
Sass Mixins Library

**Mixins**

* [`box-sizing`](#box-sizing)
* [`transition`](#transition)
* [`translateY`](#translateY)
* [`user-select`](#user-select)

**Flex Mixins**

* [`align-items`](#align-items)
* [`inline-flex`](#inline-flex)
* [`justify-content`](#box-sizing)


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

### transition
```scss
@minclude transition($args...)
```

```scss
@mixin transition($args...) {
  -webkit-transition: $args;
  -moz-transition: $args;
  transition: $args;
}
```

### translateY
```scss
@include translateY($value)
```

```scss
@mixin translateY($value) {
  -webkit-transform: translateY($value);
  -moz-transform: translateY($value);
  -ms-transform: translateY($value);
  transform: translateY($value);
}
```

### user-select
```scss
@include user-select($value)
```

```scss
@mixin user-select($value) {
  -webkit-user-select: $value;
  -moz-user-select: $value;
  -ms-user-select: $value;
  user-select: $value;
}
```

### align-items
```scss
@include align-items($value)
```

```scss
@mixin align-items($value) {
  -webkit-box-align: $value;
  -moz-box-align: $value;
  -ms-flex-align: $value;
  -webkit-align-items: $value;
  align-items: $value;
}
```

### inline-flex
```scss
@include inline-flex
```

```scss
@mixin inline-flex {
  display: -webkit-inline-box;
  display: -moz-inline-box;
  display: -webkit-inline-flex;
  display: -ms-inline-flexbox;
  display: inline-flex;
}
```

### justify-content
```scss
@include justify-content($value)
```

```scss
@mixin justify-content($value) {
  -webkit-justify-content: $value;
  -moz-justify-content: $value;
  justify-content: $value;
}
```