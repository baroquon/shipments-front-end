## Install an Ember Front-End with a Rails Backend Using Ember CLI

I start out building up an Ember App using Ember CLI and Ember Data. Then I build a rails backend and tie the to together. I chose Ember CLI over Ember because it offers a more robust shell, and gives you access to the ember command line runner that includes, among other things, a ‘new’ command, server, and generators.

First, you need to get Ember CLI up and running. 

## Install Ember CLI

    npm install -g ember-cli

## Install Bower to manage front-end dependencies 

    npm install -g bower

## Install SASS

    npm install --save-dev broccoli-sass
    mv app/styles/app.css app/styles/app.scss

It is important to name your app stylesheet app.scss if you are running sass. Broccoli is configured to look for this specific file (it looks for app.less if you are using less as your preprocessor). 

Generate your new project and get it running by typing: 

    ember new front-end-spa
    cd front-end-span
    ember server

## Your app will be running here:

    http://localhost:4200

## Your tests - Ember CLI is awesome for tests you can be see them here:

    http://localhost:4200/tests

## Install Bourbon, Neat, Bitters

    gem install bourbon
    gem install neat
    gem install bitters

    bourbon install
    neat install
    bitters install

    Probably need to import here… eh hell I’ll do it. This breaks it.



