# Mambo UI toolkit
Mambo-UI is a toolkit for building Front-end code for a new Areas intranet project: Mambo.
Mambo-UI is based on ["Fabricator"](https://github.com/fbrctr/fabricator)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisities

What things you need to install the software and how to install them

```
git / node / npm / bower
```
### Installing

A step by step series to get a development env running

First clone the repository

```
$ git clone https://github.com/gatoenano/Mambo-UI.git
```

Go to the main folder directory at project and install npm dependencies

```
$ npm install
```

Install bower dependencies

```
$ bower install
```

### Run a static server

Start the development environment by running

```
$ npm start
```

Then, points the browser url bar to:

```
http://localhost:3000
```

The gulplfile, remains listening for changes on files, if changes occurs, then reloads the browser


### Create an optimized build

Once you're ready to deploy your toolkit, run the following command to run an optimized build

```
$ npm run build
```

### Create a new svg sprite

To include a new svg file into the sprite svg, just it has to put the new file inside the directory:

```
src/assets/toolkit/images
```

Then, run the gulp task to create the new sprite:

```
gulp sprite
```

Automatically it creates the css and svg files ready to use