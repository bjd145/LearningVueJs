# LearningVueJs

## Install Tools
* Command Line - npm install -g @vue/cli
* DevTools - npm install -g @vue/devtools
* Single Vue File - npm install -g @vue/cli-service-global

## Hello World Example
* HTML - HelloWorld/hello.html
* SCF  - HeloWorld/hello.vue

### Run Hello World
* npm install http-server -g
* Via HTML - http-server.cmd .\HellWorld\hello.html
* Via Vue Single Component File - vue serve hello.vue

## Directives 
* Serveral examples of Vue.js Directives 

## Create Vue + TypeScript Project
* vue create typescript
    * Follow wizard to select components - TypeScript, PWA Support and Linter
    * Selected defaults for other questions
* cd typescript
* npm run serve
* git log 
    * vue-cli automatically creates a git repo for you

##  Single Vue File Application
* * Create a file named DistributionExample/app.vue
* Test with - vue serve app.vue
* Create a build for production - vue build app.vue
    * Creates a dist folder to deploy 

## Debug a Page
* vue-devtools
* Add <script src="http://localhost:8098"></script> to the top of your page that you want to inspect