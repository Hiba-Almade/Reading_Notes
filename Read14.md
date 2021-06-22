# CSS Transforms, Transitions, and Animations

## CSS Transforms:

The `translate()` CSS function repositions an element in the horizontal and/or vertical directions. 

Its result is a `<transform-function>` data type. This transformation is characterized by a two-dimensional vector. Its coordinates define how much the element moves in each direction.

`>>` The transform property applies a 2D or 3D transformation to an element. This property allows you to rotate, scale, move, skew, etc., elements.

**With the CSS transform property you can use the following 2D transformation methods:**
1. translate()
2. rotate()
3. scaleX()
4. scaleY()
5. scale()
6. skewX()
7. skewY()
8. skew()

![css](https://i7x7p5b7.stackpathcdn.com/codrops/wp-content/uploads/2014/12/transform-origin-examples.png)

---- 

## CSS Transitions:

CSS transitions allows you to change property values smoothly, over a given duration.

A transition occurs when a CSS property changes from one value to another value over a period of time. You can create CSS Transitions with the transition property: .`selector { transition: property duration transition-timing-function delay; }`

`>>` CSS transitions provide a way to control animation speed when changing CSS properties. Instead of having property changes take effect immediately, you can cause the changes in a property to take place over a period of time.

* ***To create a transition effect, you must specify two things:***
    1. the CSS property you want to add an effect to
    2. the duration of the effect
> Note: If the duration part is not specified, the transition will have no effect, because the default value is 0.

![css](https://www.litmus.com/wp-content/uploads/2020/04/a-simple-guide-to-understanding-css-animations-in-email.png)

---

## CSS Animations

**What are CSS Animations?**

**An animation lets an element gradually change from one style to another.**


`>>` You can change as many CSS properties you want, as many times as you want.


CSS animations make it possible to animate transitions from one CSS style configuration to another. Animations consist of two components, a style describing the CSS animation and a set of keyframes that indicate the start and end states of the animation's style, as well as possible intermediate waypoints.

> CSS allows animation of HTML elements without using JavaScript.


![css](https://coursework.vschool.io/content/images/2016/08/transition_example2.png)