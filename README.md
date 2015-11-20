# SSGS - Smart and simple grid system written in LESS

## Features
- written in LESS
- create grids on demand, on the fly
- fluid
- "dont overthink it" approach
- works in all browsers
- works on all devices
- lightweigt - 4kb
- super fast
- easy to use
- easy to modify
- free to use and abuse (MIT licence)

## Demo
Please see demo.html **or:**
#### Online demo:
http://codepen.io/riogrande/pen/LpgRvV

## Default column widths:
12 - 100%

11 - 91.667%

10 -  83.333%

9 - 75%

8 - 66.667%

7 - 58.333%

6 - 50%

5 - 41.667%

4 - 33.333%

3 - 25%

2 - 16.666%

1 - 8.333%

## Media queries
##### > 1199px - widescreens
##### < 1199px , >= 960px smaller screens
##### < 959px , >= 768px tablets
##### < 767px mobile

## LESS variables
`@row_wide_screen` - width of container > 1399px, default = 80% of the browser

`@row_1200-1400` - width of container between 1200 and 1399px, default = 90% of the browser

`@row_960-1200` - width of container between 960 and 1199px, default = 90% of the browser

`@row_tablet` - width of container between 768 and 959, default = 95% of the browser

`@gutter` - margin between columns > 1199px, default = 1% (1% from left and 1% from right)

##### Mobile row is not a variable, its default value is 100%

## Usage
### 1. Edit the grid.less
Create your grid, define widths and gutter and you are ready to go! Simple as that. What else do you need?
### 2. Add SSGS grid to your project
##### Call via css
`<link rel="stylesheet" href="grid.css">`  **or:**
##### Copy CSS and add to your project
### 3. Add SSGS HTML
##### Names: 
`row` = container

`span1` to `span12` = columns from 1 to 12
##### HTML: 
```
<div class="row">

  <div class="span12">grid 12</div>
  
  <div class="span8">grid 8</div>
  <div class="span4">grid 4</div>
  
  <div class="span7">grid 7</div>
  <div class="span5">grid 5</div>
  
  <div class="span6">grid 6</div>
  <div class="span6">grid 6</div>
  
  <div class="span4">grid 4</div>
  <div class="span4">grid 4</div>
  <div class="span4">grid 4</div>
  
  <div class="span3">grid 3</div>
  <div class="span3">grid 3</div>
  <div class="span3">grid 3</div>
  <div class="span3">grid 3</div>
  
</div>
```

## Made with (thanks)
- [LESS.js](http://lesscss.org/)
- [Codepen](http://codepen.io)
