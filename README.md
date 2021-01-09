<h1 align="center">Simple CSS Animations</h1>
<p align="center">CSS Helper for <a href="https://animista.net/">Animista.net</a></p>

## What are we talking about

We are talking about a CSS helper for simple animations.
Its based upon Animista.net content and let you apply animation to your html elements simply adding a combination of classes
## How to install

```
npm install simple-css-animations
```

<br/>

## How to use

Method 1: add the following in your index.html
```css
<link rel="stylesheet" type="text/css" href="./node_modules/simple-css-animations/index.css">
```

or Method 2: you can include the css file in your style

```css
@import "./node_modules/simple-css-animations/index.css"
```
<br/>

## Example

Use a combination of classes in order to apply your desired animation
```html
<h2 class="ani-text-focus-in ani-2000 ani-fill-forwards ani-delay-1000">Hello!</h2>
```

<br/>

## Available Classes

- ### ani-{name} <h6>Specifies the animation name</h6>
  -  name is one of those available in https://animista.net/
 
  - examples: "ani-scale-up-center", "ani-flip-in-hor-bottom", "ani-slide-in-elliptic-top-bck"
  

- ### ani-{duration} <h6>Specifies the animation duration in ms</h6>
  -  duration is a number <b>multiple of 100</b> 
  -  min: `100`
  -  max: `10000`
  
  - examples: "ani-100", "ani-3300", "ani-4200"
  
- ### ani-delay-{delay} <h6>Specifies the animation delay in ms</h6>
  -  delay is a number <b>multiple of 100</b> 
  -  min: `100`
  -  max: `10000`
  
  - examples: "ani-delay-200", "ani-delay-3200", "ani-delay-5200"
  
- ### ani-direction-{direction} <h6>Specifies the animation direction</h6>
  
  -  direction can be : `normal`, `reverse`, `alternate`, `alternate-reverse`, `initial`, `inherit`
  
  - examples: "ani-direction-normal", "ani-direction-alternate", "ani-direction-alternate-reverse"

- ### ani-count-{count} <h6>Specifies the animation iteration count</h6>
  
  -  count can be : `1, 2, .., 100`, `infinite`, `initial`, `inherit`
  
  - examples: "ani-count-10", "ani-count-infinite", "ani-count-2"
       
- ### ani-timing-{timing} <h6>Specifies the animation timing function</h6>
  
  -  timing can be : `linear`, `ease`, `ease-in`, `ease-out`, `ease-in-out`, `step-start`, `step-end`, `initial`, `inherit`
  
  - examples: "ani-timing-ease-in", "ani-timing-linear", "ani-timing-ease-in-out"

- ### ani-fill-{fill} <h6>Specifies the animation fill mode</h6>
  
  -  fill can be : `none`, `forwards`, `backwards`, `both`, `initial`, `inherit`
  
  - examples: "ani-fill-backwards", "ani-fill-forwards", "ani-fill-none"
        
## License

MIT @ Davide Turrini [(davide-turrini)](https://github.com/davide-turrini)

(Please note: This is my third try to publish something on npm! Any kind of feedback or contribution is more than welcome)
