# Node Express Ecommerce

in this file i would like to record the steps of my project.. i will assume that you already have experience manipulating node packages using npm and that you have node installed on your conputer

## step-1) creating the basic folder structur und displaying the first page

- create the frontend folder in your project folder
- create the frontend/public/index.html page with a basic html content
- create the frontend/public/assets/css/style.css file and link it in index.html
- open a new terminal and move to the frontend folder _cd frontend_
- install the live server package as Dev dependencie _npm install live-server --dev_
- create your start command "start": "live-server public --verbose"

## step-2) let's setup our project to be able to use bootstrap and sass

(this step is optional.. your don't need this step if you are not using bootstrap and sass)
follow the steps on this page: https://getbootstrap.com/docs/5.2/getting-started/webpack/

## step-3) let's now create the static site

- go to index.html and create the static site
  (create a basic homepage layout for the Header and the footer)
  (just create a basic layout content..)
- style your homepage layout
  - install sass globaly (npm install -g sass) using git bash if you are on window
