# booking-app

### Flexbox 101 Properties:

_flex: 0 0 18%_

Syntax: flex-grow, flex-shrink, flex-basis

**flex-grow** - specifies how much of the flex container's remaining space should be
assigned to the flex item's main size

**flex-shrink** - sets the flex shrink factor of a flex item. If the size of all flex items is larger than the flex
container, items shrink to fit according to flex-shrink

**flex-basis** - sets the initial main size of a flex item.

### Grid helpful info:

**fr** - fractional unit, it expands to all the white space that it can occupy.

**span** - you can use span to span through element rather than writing the next col / row

**square brackets [ ]** - you can use them to name a grid line, you have to place them somewhere to start from and where
to end

**grid-template-areas** - specifies named grid areas, establishing the cells in the grid and assigning them names.

- You can assign those names afterwards to normal grid properties such as grid-row / grid-column etc.

**Explicit grid** - the grid which we define with our modified properties

**Implicit grid** - the grid which is automatically applied if there are not enough grid proportions for the items.

**max-content** - represents the intrinsic maximum width or height of the content. For text content this means that the
content will not wrap at all even if it causes overflows

**min-content** - represents the intrinsic minimum width of the content. For text content this means that the content
will take all soft-wrapping opportunities, becoming as small as the longest word

