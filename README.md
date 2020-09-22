# Conway's Game of Life
![ts](https://badgen.net/badge/Built%20With/TypeScript/blue) [![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
An implementation of Conway's Game of Life using Typescript and React Hooks.

## Table of Contents
- [Background](#background)
- [Install](#install)
- [Usage](#usage)
	- [Static Site](#static-site)
- [Maintainer](#maintainer)
- [Contributing](#contributing)
- [License](#license)

## Background

This project was created as an excuse to finally learn TypeScript as well as strengthen my understanding of React Hooks. I first learned of [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) in my algorithms class during my undergrad at [MSU Denver](https://www.msudenver.edu/), and decided it was a good project requiring state manipulation that would be perfect for React Hooks, also choosing this as my first TypeScript project.

## Install

This project uses [node](http://nodejs.org) and [npm](https://npmjs.com). Go check them out if you don't have them locally installed.

## Usage

To use this application, clone the repository or download and extract it to a location of your choice. Afterwards, navigate to the cloned repository in your terminal and install the npm dependencies.

```sh
$ npm install
```

After dependencies have been installed, you can start the development environment which will start the node server as well as a self-refreshing instance of the application in your default web browser.

```sh
$ npm start
```

### Static Site

If you would like a static, minified, hostable version of the application, simply run the create-react-app build script

```sh
$ npm run build
```

This will generate a `/build` directory in the root of the project which you can directly host on your provider of choice.

## Maintainer

[@RyanHiller](https://github.com/RyanHiller)

## Contributing

Feel free to [open an issue](https://github.com/RyanHiller/Game-of-Life-TS/issues/new) or make a PR.

## License

[MIT](LICENSE.md) © Ryan Hiller