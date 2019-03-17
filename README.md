# [msoe.dev](https://msoe.dev/) live HTML
> My First Ever Vue Js Website

come take a look at the code for msoe.dev

## collaboration

feel free to contribute in any way 

* create a feature request
* post an issue on this github repository and I will try my best to document and fix the thang
* create a pull request to add improvements to the website

## How to run this environment

### NPM CLI

>**recommended for development**

1. `cd msoe_dev_app`
2. if it is your first time, you may have to run `sudo npm install` here to install the node_modules.
2. `npm run serve`

### Docker

>**recommended for deployment**

1. `docker-compose up`
2. http://localhost:8080/

## How I set up Vue and Element for this Project

*[tutorial i followed](https://github.com/ElementUI/vue-cli-plugin-element)*

### 1. install vue

`sudo npm install -g @vue/cli`

`sudo npm install -g @vue/cli-service-global`

### 2. create vue project

`vue create msoe_dev_app`

When prompted: 

`? Please pick a preset: default (babel, eslint)`

### 3. add element to project

`cd msoe_dev_app`

`vue add element`

**note** i chose to fully import element and overwrite Element's SCSS variables.

### 4. run it

`sudo npm install`

`npm run serve`
* http://localhost:8080/ 
