
# TKAnimatedCheckButton

Animated Check Button inpired by
https://dribbble.com/shots/1631598-On-Off
and
http://robb.is/working-on/a-hamburger-button-transition/


# Usage

## This is SubClass of UIButton

``` swift
self.button = TKAnimatedCheckButton(frame: CGRectMake(133, 133, 54, 54))
```

## How to toggle
``` swift
func toggle() {
  self.button.checked = !self.button.checked
}
```