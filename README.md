## ReVeRIES starter kit

> A starting point for building serious games web app from JSON files


### Demo
The repo includes a basic demo in example.json


## Getting Started

To take advantage of ReVeRIES starter kit you need to:

1. Get a copy of the code : git clone https://github.com/gick/revereries-project.git
2. Install the dependencies if you don't already have them : from the reveries-project directory,  $ npm install $ bower install
3. Run the code locally : from the reveries-project directory, $ gulp serve, this will serve the website on port 8080
4. Run the code for production : from the reveries-project directory $ gulp, this will create a /dist directory that you can serve using apache2 for example



#### Quick-start (for experienced users)

With Node.js installed, run the following one liner from the root of your REVERIES download:

```sh
npm install -g gulp bower && npm install && bower install
```

#### Prerequisites (for everyone)

The full starter kit requires the following major dependencies:

- Node.js, used to run JavaScript tools from the command line.
- npm, the node package manager, installed with Node.js and used to install Node.js packages.
- gulp, a Node.js-based build tool.
- bower, a Node.js-based package manager used to install front-end packages (like Polymer).

**To install dependencies:**

1)  Check your Node.js version.

```sh
node --version
```

The version should be at or above 0.12.x.

2)  If you don't have Node.js installed, or you have a lower version, go to [nodejs.org](https://nodejs.org) and click on the big green Install button.

3)  Install `gulp` and `bower` globally.

```sh
npm install -g gulp bower
```

This lets you run `gulp` and `bower` from the command line.

4)  Install the starter kit's local `npm` and `bower` dependencies.


This installs the element sets (Paper, Iron, Platinum) and tools the starter kit requires to build and serve apps.

### Development workflow

#### Serve / watch

```sh
gulp serve
```

This outputs an IP address you can use to locally test and another that can be used on devices connected to your network.

#### Run tests

```sh
gulp test:local
```

This runs the unit tests defined in the `app/test` directory through [web-component-tester](https://github.com/Polymer/web-component-tester).

To run tests Java 7 or higher is required. To update Java go to http://www.oracle.com/technetwork/java/javase/downloads/index.html and download ***JDK*** and install it.

#### Build & Vulcanize

```sh
gulp
```

Build and optimize the current project, ready for deployment. This includes vulcanization, image, script, stylesheet and HTML optimization and minification.


