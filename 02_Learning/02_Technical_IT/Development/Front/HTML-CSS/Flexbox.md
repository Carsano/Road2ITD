---
tags:
  - dev
  - css
  - html
---
# Introduction
A flex container is any element hat has `display: flex`. A flex item is any element that lives directly inside a flex container
You can nest a flex container in a flex item
![[Pasted image 20250510194515.png]]

# Growing and shrinking
`flex`is a short hand for 3 properties : 
- `flex-grow`
- `flex-shrink`
- `flex-basis`
```css
div {
	flex: 1;
}
```
That equals to `flex-grow:1;`, `flex-shrink:1;`and `flex-basis:0;`
You can also put `flex: 1 1 0;`
By saying `flex:1`the element should grow the same amount of every other
By saying `flex: 2`to a particular element, it will be twice bigger that the other elements in the flex container.

`flex-shrink`is applied when the flex elements are bigger than the flex container, forcing them to shrink inside it. If you don't want items to shrink then put `flex-shrink: 0`
