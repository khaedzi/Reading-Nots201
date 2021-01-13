

# Animation 
we use it to allow the element move from state to state in sequance
Animations Keyframes
we use the animation name and give it multiple vlaue to determin how it move
syntax : animation-name: slide;
after we use the animation name we use the @keyframes keyword to give the name it is movement
syntax :
@keyframes slide { 0% { ` left: 0; top: 0; } 50% { left: 244px; top: 100px; } 100% { left: 488px; top: 0; } }`
# Transforms
the Transform property in css give us the ability to modify the position os the element.
### there are two value for Transform:
 * two-dimensional
 * three-dimensional

# Transform Syntax
#### there is multiple syntax for each browsre:
* we use to chrome: -webkit-transform
* we use to firefox: -moz-transform
* we use for all browsre : transform


# Transitions
it is the ability to make elemnt to change it is state to another
### we can use different state and we call it pseudo-classes.:
* :hover
* :focus
* :active
* :target
## for the transition ther are four property we can use :
* transition-property
* transition-duration
* transition-timing-function
* transition-delay.
* transition-property

## transition-duration
we determine the time to do the change
syntax : transition-duration: 1s;
we can use two value for it second and millisecond
transition-timing-function
we determine the type of change
syntax : transition-timing-function: linear;
it take four value:
* linear
* ease-in
* ease-out
* ease-in-out.


also we use 
* transition-delay.
