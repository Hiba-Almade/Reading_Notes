# CSS Layout:

## **Layout Types:**

***Pages can be fixed width or liquid (stretchy) layouts***
`>>` So let's discuss CSS layout types: fixed (sometimes referred to as static), elastic, and fluid (sometimes referred to as liquid).

* Fixed (px):

    In a fixed (static) layout, elements are sized using pixels. One of the nice things about this is that our elements will be the same size on all screens. It is a measurement that is independent and uneffected by the size of the device we are viewing from. The only downside is if we create an element that is wider or taller than the device size we will see scrollbars, and the user will have to scroll to see the rest of the content that is out of view. Or, if the screen size is much larger than our element there may be substantial white space around the element. In other words we are not neccesarily utilizing all of the screen space.

* Elastic (em):

    Elastic layouts size elements using (em) ems. An em is a typographic unit that describes a the size of a single character, typically the default is 1em = 16 px in size.

* Fluid (%):

    Fluid (liquid) layouts size elements using (%) percents. This allows for a layout that will stretch and expeand or contract to the size of the users device. This allows developers to make use of the entirety of space on the screen. Also your users will never see scrollbars if used it is implemented correctly. Some drawbacks would be that as designers we lose some control over where media and text will wrap as screens change size on different devices.

--- 

*we used `<div>` to containing elements to group together sections of a page.*

*Browsers display pages in normal flow unless you specify `relative`, `absolute`, or `fixed` positioning.*

*The `float` property moves content to the left or right of the page and can be used to create multi-column layouts..*

![layout](https://s3.amazonaws.com/noupe/img/css-layouts24.gif)
