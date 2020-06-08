# Wrap with emo

An API for warp text with emoji.

Installation and Usage
----------------------

Wrap with emo supports stable versions of Node.js 8.15.0 and later. You can install
Wrap with emo globally or in your project's `node_modules` folder.

To install the latest version on npm globally (might require `sudo`;
[learn how to fix this](https://docs.npmjs.com/resolving-eacces-permissions-errors-when-installing-packages-globally)):

    npm install -i wrap-with-emo


## usage
    var wrapWithEmo = require("wrap-with-emo")
    var text = "text"
    var result = wrapWithEmo(text)
    console.log(result)
