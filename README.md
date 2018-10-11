# Float Based Grid Layout system

A simple based layout system built with float property and SASS


## Example

![Screenshot01][1]  

[1]: ./screenshots/screenshot.png


## Retrieve code

* `$ git clone https://github.com/raheemazeezabiodun/float-based-grid-layout-system.git`
* `$ cd float-based-grid-layout-system`
* `yarn install`


## Usage
If you are writing SASS(SCSS), copy the sass folder to your project
If you prefer to use CSS, generate the css file by compiling sass using the following command
* `yarn run compile:sass`

To use this float based grid system,

wrap the column in a row container

`<div class="row">`

Then call any of the column class e.g
`<div class="col-1-of-4">`


```
<div class="row">
    <div class="col-1-of-2">Col 1 of 2</div>
    <div class="col-1-of-4">Col 1 of 4</div>
    <div class="col-2-of-4">Col 2 of 4</div>
</div>
```

## Classes
* `<div class="col-1-of-2"></div>`
* `<div class="col-1-of-3"></div>`
* `<div class="col-1-of-4"></div>`
* `<div class="col-2-of-3"></div>`
* `<div class="col-2-of-4"></div>`
* `<div class="col-3-of-4"></div>`


## TODO
Do you want to contribute to this project? A quick way to do that is to use the
function in `abstracts/_functions.scss` in `layouts/_grid.scss`