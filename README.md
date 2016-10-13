Not Linking
===

Hot linking getting you down? Stop them linking with Not Linking.

This tiny express module checks the Referrer and makes sure that this file is only be referenced by the server it's hosted on.

Installation
---

```
npm install notlinking
```


Usage
---

```js
const express = require('express');
const notlinking = require('notlinking');

app.use(notlinking());

// Available options
app.use(notlinking({
	foundryUrl : 'http://yourfavourite.foundry',
	message    : 'Customisable message for would be thieves'
}));
```

