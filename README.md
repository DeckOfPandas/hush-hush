# h u s h h u s h

## Introduction
This repo described here contains the source code for the Hush Hush website. The site uses jekyll, HTML, JavaScript, and CSS/Sass, built and optimised using Gulp, and is deployed via Netlify. 

## Licence
Source code is licensed under GPLv3. Website content is licensed under CC BY. All IP remains with Hush Hush.

## Overview

### Building locally
#### Initial setup 
* `git clone` repo
* `bundle install` to install list of gems in Gemfile  
* `npm install` to install list of node packages in packages.json  

#### Then
* `gulp serve` builds the site and serves it at `localhost:3000
* The gulpfile has other build options, including `gulp clean`
* Browser automaticlly refreshes with changes etc

## Gotchas
* Netlify setup build command should be `gulp` not `gulp serve`
