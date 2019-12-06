# JavaScript Common Utility Module Library

**A library of JavaScript Modules which provide commonly required utility on web apps.**

This is a collection of JavaScript modules/snippets that I've written to refer to in my work, so that myself and my team are not re-inventing the wheel. The code is often for manipulating the DOM, or providing a more accessible experience for users.

The code is intended to be used in modules, and where appropriate is written as such; i.e. for a module named `file-name.js` you'd write:

```
module.exports = {
    init: () => {
        // your code goes here
    }
};
```

You'll then require the module in your base JavaScript file like so:

```
const FileName = require("./modules/file-name");
FileName.init();
```

Note that you omit the `.js` from the end of the file name when requiring it.

This code is open-source in the sense of "*please feel free to use these in your own projects without crediting me*", but not open-source in the sense of "*raise an issue about how you'd do something better and expect a reply*". I don't mean that to sound harsh, I'm just quite busy and have other open-source projects to maintain, and this is mainly for the reference of myself and my team at work.
