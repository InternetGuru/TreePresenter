# Tree Presenter

Javascript library that creates web application with hierarchical structured presentation.

Demo: #TODO

## Requirements

List of requirements for proper library operation.

Import JS libraries:
```
<script src="./js/jquery-3.3.1.min.js"></script>
<script src="./js/outliner.min.js"></script>
<script src="./js/pdfmake.min.js"></script>
<script src="./js/vfs_fonts.js"></script>
<script src="./js/raphael.js"></script>
<script src="./js/Treant.js"></script>
<script src="./js/TreePresenter.js"></script>
```
Import CSS styles:
```
<link rel="stylesheet" href="./css/style.css">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.10/css/all.css" integrity="sha384-+d0P83n9kaQMCwj8F4RJB66tzIwOKmrdb46+porD/OvrJ+37WqIM7UoBtwHO6Nlg" crossorigin="anonymous">
```
Import no JS support:
```
<noscript><link rel="stylesheet" type="text/css" href="TreePresenter_NoJS.css"></noscript>
```

### Source data syntax
Below is a list of rules which allows the creation of the correct tree presentation. Compatibility is not guaranteed in case of non-compliance.

* All presentation content is part of one HTML file [MUST].
* HTML5 language [SHOULD].
* Valid HTML syntax [SHOULD].
* Existence of heading id [MUST].
* The content of the presentation in the element `body` [MUST].

#### Example of HTML file with presentation content
```html
<h1 id="slide1">Slide 1</h1>
<ul>
  <li>Root of the tree</li>
</ul>

<section>
  <h1 id="slide2">Slide 2</h1>
  <ul>
    <li>Slide with depth 1</li>
  </ul>
  
  <h2 id="slide3">Slide 3</h2>
  <ul>
    <li>Slide with depth 2</li>
  </ul>
  
  <h2 id="slide4">Slide 4</h2>
  <ul>
    <li>Slide with depth 2</li>
  </ul>
</section>

<h2 id="slide5">Slide 5</h2>
<ul>
  <li>Slide with depth 1</li>
</ul>

<h3 id="slide6">Slide 6</h3>
<ul>
  <li>Slide with depth 2</li>
</ul>
```

### Controls
During presentation, you can use following shortcuts, mouse and touch gesture if the device allows it.

| Key | Action |
| ------ | ------ |
| H, J, K, L | Hierarchical navigation |
| Left, right | Linear navigation |
| Up, down, enter | Title naviagation |
| Space | Zoom into slide |
| M | Slides overview |
| N | Next/previous  presentation (if exist) |
| S | Settings |
| D | Download |
| ? | Help/Shortcuts |

## Development instructions

#TODO

## Used technology
List of technologies and libraries that are used:

* [HTML5](https://www.w3schools.com/html/html5_intro.asp)
* [ECMASCRIPT 2015](http://www.ecma-international.org/ecma-262/6.0/)
* [npm](https://www.npmjs.com/)
* [SASS](http://sass-lang.com/)
* [Babel](https://babeljs.io/)
* [Rollup](https://github.com/rollup/rollup)
* [Treant.js](http://fperucic.github.io/treant-js/)
* [h5o-js](https://github.com/h5o/h5o-js)
* [pdfmake](http://pdfmake.org/index.html#/)
* [jQuery](https://jquery.com/)
