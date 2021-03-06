Clean SCSS slate
================

Includes:
* multiple color palettes as scss variables
  * [A nicer color palette](http://clrs.cc/)
  * [Windows 8 theme colors](http://www.creepyed.com/wp-content/uploads/win8ColorsPersonalize.png)
  * [Flat color UI](http://flatuicolors.com/)
* css normalize
* customizable grid by columns and gutter size
* various scss mixins (transitions, animations, keyframes)
* media queries and breakpoints
* global settings + browser fixes


### Layout
```
├── public
|   ├── stylesheets
|   |   ├── style.css
|   |   └── scss
|   |       ├── style.scss
|   |       |
|   |       ├── _base.scss
|   |       ├── _main.scss
|   |       |
|   |       ├── base
|   |       |   ├── _normalize.scss
|   |       |   ├── _variables.scss
|   |       |   ├── _global.scss
|   |       |   ├── _extra.scss
|   |       |   └── _grid.scss
|   |       |
|   |       └── main.scss
|   |           └── _file.scss
```

 
## Installation
To view color palettes and basic styling, clone the repo and run `index.html`.

To install via Bower:
```bash
$ bower install clean-scss-slate
```


