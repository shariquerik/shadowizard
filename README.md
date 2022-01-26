# What is this?

Get perfect shadows every time for the non-designer.

# Installation

`npm i shadowizard --save`

Then...

```
import { shadowizard } from 'shadowizard';

shadowizard({
	shadow_type: 'soft',
	padding: false
});
```

## Options

Shadowizard supports 2 options, both of which are optional:

* *shaow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Dafaults to false)