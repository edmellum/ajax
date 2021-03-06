ajax
====

Standalone AJAX library inspired by jQuery/zepto

## Installation

You can use [component](https://github.com/component/component):

```
component-install ForbesLindesay/ajax
```

Then load using:

```JavaScript
var ajax = require('ajax');
```

Or load using a script tag (the file is available in downloads)

```html
<script src="ajax.min.js"></script>
```

Then just refer to it in your script as `ajax`

## API

### ajax(url, settings)

**url** A string containing the URL to which the request is sent.
**settings** A set of key/value pairs that configure the Ajax request. All settings are optional. A default can be set for any option with `ajax.settings`. See ajax(settings) below for a complete list of all settings.

### ajax(settings)

**settings** A set of key/value pairs that configure the Ajax request. All settings are optional. A default can be set for any option with `ajax.settings`.

For a list of available settings see:

http://api.jquery.com/jQuery.ajax/