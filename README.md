<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="img/favicon.png" alt="Project logo"></a>
</p>

<h3 align="center">Nexter</h3>
Deployment Link : https://meek-cranachan-0225aa.netlify.app/

---

<p align="center"> Own your home, own your freedom
    <br> 
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built_using)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>

The purpose of this project is to create the landing page for a company that sells premium houses.

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

You will need to have [Nodejs](https://nodejs.org/en/) in your system.

Check the documentation to install it on your system.

### Installing

Once you have Node Js on your system. You can see in the package.json all the scripts.

```
 "scripts": {
    "watch:sass": "node-sass sass/main.scss css/style.css -w",
    "devserver": "live-server",
    "start": "npm-run-all --parallel devserver watch:sass",
    "compile:sass": "node-sass sass/main.scss css/style.comp.css",
    "prefix:css": "postcss --use autoprefixer -b \"last 10 versions\" css/style.comp.css -o css/style.prefix.css",
    "compress:css": "node-sass css/style.prefix.css css/style.css --output-style compressed",
    "build:css": "npm-run-all compile:sass prefix:css compress:css"
  },

package.json

```

## 🎈 Usage <a name="usage"></a>

<img width=1034 height=500 src="screenshots/screenshot-1.PNG" alt="Project logo"></a>

You can make changes in the components inside the sass folder.
Run **npm watch:sass** to see in the browser all the changes that you do in the page.

## 🚀 Deployment <a name = "deployment"></a>

You can deploy this page to Netlify.

## ⛏️ Built Using <a name = "built_using"></a>

- [HTML](https://nodejs.org/en/) - Markup Language
- [CSS](https://nodejs.org/en/) - Stylesheets
- [SASS](https://sass-lang.com/) - CSS Preprocessor

## ✍️ Authors <a name = "authors"></a>

- [@jonasschmedtmann](https://github.com/jonasschmedtmann) - Idea & Initial Work

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- CSS Udemy Jonas Course
- Natours
