<p align="center">
    <a href="http://medfast.ml/s3//" target="_blank">
        <img src="https://github.com/lucymakori/README/blob/main/medfast_logo.png" width="400" alt="medfast" />
    </a>
</p>

Medfast payment module
------------
Payment system for issuing and printing bank cheques,record management,scheduling events and keep accounting records.


Installation
------------

- clone this repository.
- install dependencies using yarn install or npm install.
- Start development server using yarn dev or npm run dev.

### Directory Structure

```
assets
    icons/              contains application icons 
    img/                contains application images 
    js/                 contains application javascript files
    scss/               contains application css and scss files    
build                   contains static files that can be hosted in web servers
components              contains imported files for rendering functionalities
lang                    contains language defination
layouts                 contains layout files for page defination
middleware              contains files that are loaded before rendering a page
node_modules            contains external libraries and packages that power the app
pages
    accounting/         contains accounting files
    banking/            contains banking files
    calender/           contains date files
    payments/           contains payment files
    settings/           contains settings files
plugins                 contains JavaScript files that are injected as functions and constants
static                  contains files that are automatically mapped and saved
store                   contains vuex store files to manage the state of app components
nuxt.config.js          contains app setting for asset builder to load and build
package.json            contains defines app dependencies and start scripts commands

```

