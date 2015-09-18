# jenkins-ace-editor
NPM wrapper for the ACE Editor (via [Brace](https://github.com/thlorenz/brace)), allowing it to be used as
an exported Jenkins module.

# Install

```
npm install --save jenkins-ace-editor
```

# Usage

```javascript
var ace = require('jenkins-ace-editor');
var editor = ace.edit('the-editor');
```

See the [ACE Editor Docs](http://ace.c9.io/#nav=howto) for a full list of modes and themes.
