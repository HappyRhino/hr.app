hr.app [![Build Status](https://travis-ci.org/HappyRhino/hr.app.png?branch=master)](https://travis-ci.org/HappyRhino/hr.app)
=============================

> Application manager

## Installation

```
$ npm install hr.app
```

### Documentation

```js
var Application = require("hr.app");

var MyApp = Application.extend({
    name: "My Awesome App",

    router: {
        "user/:username": "showUser"
    },

    showUser: function(username) {

    }
});


var app = new MyApp();
app.router.start()
```

