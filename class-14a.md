# Transitions & Animations

## Transitions

A transition must occur when an element changes state, and various styles must be designated for each stage. The :hover, :focus, :active, and :target pseudo-classes make selecting styles for different situations a breeze.

Transition-property, transition-duration, transition-timing-function, and transition-delay are the four transition-related qualities in total. The first three are the most popular, although not all of them are required to build a transition.

```CSS
.box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
}
```

## Animation

Transitions are ideal for these kind of single-state changes since they help to build out visual interactions from one state to the next. When additional control is needed, however, transitions must have numerous states. In exchange, animations take over where transitions leave off.

```CSS
.stage:hover .ball {
  animation-name: slide;
  animation-duration: 2s;
  animation-timing-function: ease-in-out;
  animation-delay: .5s;
}
```
