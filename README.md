```
______                          _     ______       _ _                 _       _       
| ___ \                        | |    | ___ \     (_) |               | |     | |      
| |_/ /___ _ __ ___   __ _ _ __| | __ | |_/ / ___  _| | ___ _ __ _ __ | | __ _| |_ ___ 
|    // _ \ '_ ` _ \ / _` | '__| |/ / | ___ \/ _ \| | |/ _ \ '__| '_ \| |/ _` | __/ _ \
| |\ \  __/ | | | | | (_| | |  |   <  | |_/ / (_) | | |  __/ |  | |_) | | (_| | ||  __/
\_| \_\___|_| |_| |_|\__,_|_|  |_|\_\ \____/ \___/|_|_|\___|_|  | .__/|_|\__,_|\__\___|
                                                                | |                    
                                                                |_|                    

```

This is a boilerplate to use [remark](https://github.com/gnab/remark) easily with [Gulp](http://gulpjs.com/), [Jade](http://jade-lang.com/) and [Stylus](http://learnboost.github.io/stylus/).

To know more about remark and how to use, [read the docs here](https://github.com/gnab/remark/wiki).

## Getting Started

### Installation

First of all, install the dependencies to run this boilerplate.

- [NodeJS](http://nodejs.org/)
- [GulpJS](http://gulpjs.com/)

```sh
# Clone this repository
$ git clone git@github.com:brenopolanski/remark-boilerplate.git my-presentation
$ cd my-presentation

# install dependencies
$ npm install
# run tasks and serve
$ gulp
```
With the commands above, you have everything to start.

```sh
.
├── build
│   ├── css
│   │   └── main.css
│   ├── index.html
│   └── js
│       ├── main.js
│       └── vendor
│           ├── remark-fallback.js
│           ├── remark-language.js
│           └── remark.min.js
├── gulp
│   ├── index.js
│   ├── paths.js
│   └── tasks
│       ├── browser-sync.js
│       ├── default.js
│       ├── deploy-pages.js
│       ├── imagemin.js
│       ├── jade.js
│       ├── js.js
│       ├── stylus.js
│       └── watch.js
├── gulpfile.js
├── package.json
├── README.md
├── src
│   ├── js
│   │   ├── main.js
│   │   └── vendor
│   │       ├── remark-fallback.js
│   │       ├── remark-language.js
│   │       └── remark.min.js
│   ├── slides
│   │   ├── slide-1.md
│   │   ├── slide-2.md
│   │   └── slide-3.md
│   ├── styl
│   │   ├── main.styl
│   │   ├── remark-themes
│   │   │   └── default.styl
│   │   └── vendor
│   │       └── remark.styl
│   └── templates
│       ├── inc
│       │   ├── head.jade
│       │   └── scripts.jade
│       └── index.jade
└── tree.txt
```
