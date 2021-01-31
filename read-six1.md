## color

  **The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:**

1. rgb values:
These express colors in terms of how much red, green and blue are used to make it up. For
example: `rgb(100,100,90)`


2. hex codes:
These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign.
 example: `#ee3e80`

3. color names:
There are 147 predefined color names that are recognized by browsers.
 example:`DarkCyan`

### Background color:
1. For change backgroud for page you will use:
 `body {`
`background-color: rgb(200,200,200);}`
 
2. For change background for paragraph or h1.. use:
`h2 {`
`background-color: #ee3e80;}`

`p {`
`background-color: white;}`


**The CSS3 rgba property allows you to specify a color, just like you would with an RGB value, but adds a fourth value to indicate opacity. This value is known as an alpha value and is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).**
 The rgba value will only affect the element on which it is applied (not child elements).

Example on color:


`<!DOCTYPE html>`
`<html>`
`<head>`
 `<title>Color</title>`
 `<style type="text/css">`
 `body {`
 `background-color: silver;`
 `color: white;`
 `padding: 20px;`
 `font-family: Arial, Verdana, sans-serif;}`
 `h1 {`
 `background-color: #ffffff;`
 `background-color: hsla(0,100%,100%,0.5);`
 `color: #64645A;`
 `padding: inherit;}`
 `</style>`
`</head>`
`<body>`
 `<h1>pH Scale</h1>`
`</body>`
`</html>`
