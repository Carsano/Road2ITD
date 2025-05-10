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
That equals to `flex-grow:1;`, `flex-shrink:1;`and `f