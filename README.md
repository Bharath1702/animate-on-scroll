# Animate while scrolling
[Live Demo](https://63850e47a04cfb5a2ae70414--creative-tiramisu-e5d737.netlify.app/)

## Step 1

Add `class=hidden` to every section we want to animate

## Step 2

Create an HTML [Intersection Observer](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API)

## Step 3

Use CSS Transition to animate

## Step 4 (optional)

Not everyone wants to watch your stupid animation again and again, use this media query to supress it:

```
@media (prefers-reduced-motion) {
  .hidden {
    transition: none;
  }
}
```
