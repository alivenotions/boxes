# Intersection Observer

* Intersection observer allows the observation of an intersection of two elements.
* It runs asynchronously, so is more performant than `onScroll` with the expensive `scrollTop` , `getBoundingClientRect` and similar properties/methods that cause [reflow](https://gist.github.com/paulirish/5d52fb081b3570c81e3a).
* Observing a `position: fixed` against the viewport is not possible as it is always relative to the viewport and in a sense is scrolling with the viewport. We can however check some other element against the viewport and set the `fixed` element to some other position value.

