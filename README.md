# HTML Starter kit

Hi. This is a starter boilder plate for html template.

## Installation

### Requirements

it's requires the following dependencies:

- [Node.js](https://nodejs.org/)

### Quick Start

Clone as your project name (like, say, `demo`), and then you'll need to follow few steps to start working on.

1. Add main project repository url like `git remote add origin git@github.com:your-repository-url`.
1. Then update package.json name to your project name (like `demo`) it's **IMPORTANT**.
1. After that open this project in terminal and run `yarn install`
1. Then Run Development Command `yarn dev` which will start dev server in `http://localhost:3000` also it will start watching `sass` and partial html files from `blocks/` and `pages/` from this html files main files are generated. all your `pages/` folder file will be a static file like index.html

### CSS/JS Loading

To load css or js please add your file to `assets/vendors/` Lets say you want to add owl-carousel so make a folder to `assets/vendors/owl-carousel` then put it's css and js file there add css file link to `blocks/styles.html` like `<link rel="stylesheet" href="assets/vendors/owl-carousel/owl-carousel.min.css" />` and add js file link to `blocks/scripts.html` like `<script src="assets/vendors/owl-carousel/owl-carousel.min.js"></script>`

## bundle

When you want to release package you have to run following command in terminal `yarn bundle` which will generate your project zip file like `demo-html-main.zip` which contains all necessary files
