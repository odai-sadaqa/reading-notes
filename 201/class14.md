## CSS Transitions
  - CSS transitions allows you to change property values smoothly, over a given duration.

***In this chapter you will learn about the following properties:***

- transition
- transition-delay
- transition-duration
- transition-property
- transition-timing-function

## How to Use CSS Transitions?
**To create a transition effect, you must specify two things:**
1. the CSS property you want to add an effect to
2. the duration of the effect

```
div {
  width: 100px;
  height: 100px;
  background: black;
  transition: width 11s;
  color:white;
  text-align: center;
}

div:hover {
  width: 600px;
}
```

```
div {
  width: 100px;
  height: 100px;
  background: red;
  transition: width 2s, height 4s;
}

div:hover {
  width: 300px;
  height: 300px;
}

div {
  width: 100px;
  height: 100px;
  background: red;
  transition: width 2s;
}
```


## the Speed Curve of the Transition
The ```transition-timing-function``` property specifies the speed curve of the transition effect.  

The ```transition-timing-function``` property can have the following values:

```ease``` - specifies a transition effect with a slow start, then fast, then end slowly (this is default)  
```linear``` - specifies a transition effect with the same speed from start to end
```ease-in``` - specifies a transition effect with a slow start  
```ease-out``` - specifies a transition effect with a slow end
```ease-in-out``` - specifies a transition effect with a slow start and end
```cubic-bezier(n,n,n,n)``` - lets you define your own values in a cubic-bezier function
The following example shows some of the different speed curves that can be used:


```
<h1>The transition-timing-function Property</h1>

<p>Hover over the div elements below, to see the different speed curves:</p>

<div id="div1">linear</div><br>
<div id="div2">ease</div><br>
<div id="div3">ease-in</div><br>
<div id="div4">ease-out</div><br>
<div id="div5">ease-in-out</div><br>

```

```
#div1 {transition-timing-function: linear;}
#div2 {transition-timing-function: ease;}
#div3 {transition-timing-function: ease-in;}
#div4 {transition-timing-function: ease-out;}
#div5 {transition-timing-function: ease-in-out;}

div:hover {
  width: 300px;
}

```


### Delay the Transition Effect
  - The transition-delay property specifies a delay (in seconds) for the transition effect

```
div {
    transition-delay: 1s;
}
```


### Transition + Transformation
  - The following example adds a transition effect to the transformation
```
div {
  width: 100px;
  height: 100px;
  background: red;
  transition: width 2s, height 2s, transform 2s;
}

div:hover {
  width: 300px;
  height: 300px;
  transform: rotate(180deg);
}
```


### The CSS transition properties can be specified one by one, like this

```
div {
  transition-property: width;
  transition-duration: 2s;
  transition-timing-function: linear;
  transition-delay: 1s;
}
```

### or by using the shorthand property transition:

```
div {
  transition: width 2s linear 1s;
}
```


# CSS Animations:
  - CSS allows animation of HTML elements without using JavaScript or Flash!


## What are CSS Animations?
1. An animation lets an element gradually change from one style to another.

2. You can change as many CSS properties you want, as many times as you want.

3. To use CSS animation, you must first specify some keyframes for the animation.

4. Keyframes hold what styles the element will have at certain times.


## The @keyframes Rule
**When you specify CSS styles inside the @keyframes rule, the animation will gradually change from the current style to the new style at certain times.**
**To get an animation to work, you must bind the animation to an element.**

```
div {
  width: 100px;
  height: 100px;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
}

@keyframes example {
  from {background-color: red;}
  to {background-color: yellow;}
}
```

**The ```animation-duration``` property defines how long an animation should take to complete. If the animation-duration property is not specified, no animation will occur, because the default value is 0s (0 seconds).**


The following example will change both the background-color and the position of the ```<div>``` element when the animation is 25% complete, 50% complete, and again when the animation is 100% complete:

```
div {
  width: 100px;
  height: 100px;
  background-color: red;
  position: relative;
  animation-name: example;
  animation-duration: 4s;
}

@keyframes example {
  0%   {background-color:red; left:0px; top:0px;}
  25%  {background-color:yellow; left:200px; top:0px;}
  50%  {background-color:blue; left:200px; top:200px;}
  75%  {background-color:green; left:0px; top:200px;}
  100% {background-color:black; left:0px; top:0px;}
}
```

### Set How Many Times an Animation Should Run
 - The animation-iteration-count property specifies the number of times an animation should run.

**The following example will run the animation 3 times before it stops:**

```
div {
  width: 100px;
  height: 100px;
  background-color: red;
  position: relative;
  animation-name: example;
  animation-duration: 4s;
  animation-iteration-count: 3;
}
```

### Run Animation in Reverse Direction or Alternate Cycles
The animation-direction property specifies whether an animation should be played forwards, backwards or in alternate cycles.

The animation-direction property can have the following values:

1. ```normal``` - The animation is played as normal (forwards). This is default
2. ```reverse``` - The animation is played in reverse direction (backwards)
3. ```alternate```- The animation is played forwards first, then backwards
4. ```alternate-reverse```- The animation is played backwards first, then forwards

The following example will run the animation in reverse direction (backwards)

```
div {
  width: 100px;
  height: 100px;
  position: relative;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
  animation-direction: reverse;
}
```


### Specify the fill-mode For an Animation
 - CSS animations do not affect an element before the first keyframe is played or after the last keyframe is played. The animation-fill-mode property can override this behavior.

The animation-fill-mode property specifies a style for the target element when the animation is not playing (before it starts, after it ends, or both).

The animation-fill-mode property can have the following values:

```none``` - Default value. Animation will not apply any styles to the element before or after it is executing
```forwards``` - The element will retain the style values that is set by the last keyframe (depends on animation-direction and animation-iteration-count)
```backwards``` - The element will get the style values that is set by the first keyframe (depends on animation-direction), and retain this during the animation-delay period
```both``` - The animation will follow the rules for both forwards and backwards, extending the animation properties in both directions

### Animation Shorthand Property
  - The example below uses six of the animation properties:

**Example**
```
div {
  animation-name: example;
  animation-duration: 5s;
  animation-timing-function: linear;
  animation-delay: 2s;
  animation-iteration-count: infinite;
  animation-direction: alternate;
```

**The same animation effect as above can be achieved by using the shorthand animation property:**

Example
```
div {
  animation: example 5s linear 2s infinite alternate;
}
```

## CSS 2D Transforms
   - CSS transforms allow you to move, rotate, scale, and skew elements.


With the CSS transform property you can use the following 2D transformation methods:

- translate()
- rotate()
- scaleX()
- scaleY()
- scale()
- skewX()
- skewY()
- skew()
- matrix()

- The translate() Method
**The translate() method moves an element from its current position (according to the parameters given for the X-axis and the Y-axis).**
```
div {
  transform: translate(50px, 100px);
}

```

The rotate() method rotates an element clockwise or counter-clockwise according to a given degree.
```
div {
  transform: rotate(20deg);
}
```

### CSS 3D Transforms
  - CSS also supports 3D transformations.

With the CSS transform property you can use the following 3D transformation methods:

- rotateX()
- rotateY()
- rotateZ()


The rotateX() method rotates an element around its X-axis at a given degree:

Example
```
#myDiv {
  transform: rotateX(150deg);
}
```