# CSS Transforms, Transitions, and Animations

## Transforms

- a technique that allows reposition and altering of elements

- can be done 2d and 3d

- not all browsers support transforms but they are definitely moving in that direction

- 2d transforms work on x and y access 

- `transform: rotate(xdeg);` roates up to 360 degrees in either direction

- scale changes size compare to original

- translate moves objects in different directions

- skew distors objects on the x or y axis

## Transitions and Animations

- are a changes in state

- transition property determines which properties will change

- transition-duration can be set to indicate how long the transition will take

- transition timing sets the speed the transition moves

- transition-delay indicates how long before the transition begins

- just `transition` can be used to declare these properties in a single line

## Animations

- for multiple points we want an element to transition we use `@keyframe`

- you can indicate duration timing and delay for animations the same way you would with a transition

- you can have animations continue from where they left off 

- fill-mode indicates how an animation shoukld be styled before or after the  animation is run

- animations can be written in shorthand the same way transitions can