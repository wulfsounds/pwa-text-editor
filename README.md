# Just Another Text Editor (J.A.T.E.)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

JATE is a progressive web-based application (PWA) that utilizes IndexedDB for storage and uses a data persistence technique that allows the program to run offline.

## Table of Contents

-   [Synopsis](#Synopsis)
-   [Technology](#Technology)
-   [Installation](#Installation)
-   [Usage](#Usage)
-   [Links](#Links)
-   [License](#License)
-   [Questions](#Questions)

## Synopsis

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Technology

Javascript
Webpack
Node
Express

## Installation

To get started, fork this repo into a text editor, then install the node package in the root folder into your repo using in the command line.

```bash
npm install
```

After installation, either use `npm run start` or `npm run start:dev` to run the application locally, then to connect to the locahost port.

To deploy the app, visit the Heroku deployment in [Links](#links)

## Usage

![screenshot 1](./src/screenshot-1.png)

![screenshot 2](./src/screenshot-2.png)

![screenshot 3](./src/screenshot-3.png)
## Links 

Repo this on [GitHub](https://github.com/wulfsounds/pwa-text-editor)

Deploy on [Heroku](https://pwa-jate-wulfsounds.herokuapp.com/)


## License

MIT License

Copyright (c) 2022 Dev Wulf

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Questions

For questions, contact me through <a href="https://github.com/wulfsounds">Github!</a>


