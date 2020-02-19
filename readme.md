# d-flex

Easy CSS positioning

### Documentation

To start using `d-flex`, add the `d-flex` class to your parent element. This should usually be a `div`.
Example:

```html
<div class="d-flex"></div>
```

This `div` will now be flexified. You can start adding the following classes to it now.

| .fill           | Adds `flex: 1`; to the element to fill up the space (if the parent is also `d-flex`)           |
| --------------- | ---------------------------------------------------------------------------------------------- |
| .text-right     | Makes the `text-align` be `right` (useful for positioning stuff to the right)                  |
| .column         | Turns the parent flex direction into a column.                                                 |
| .justify-center | Justifies the d-flex content into the center (along the main axis)                             |
| .align-center   | Moves the content into the center on the opposite axis to the main axis (e.g. y => x)          |
| .child-grow     | Makes each direct child fill up according to their content                                     |
| .child-fill     | Makes each direct child be equal width and fill up the parent's width/height depending on axis |
