# coloring-console

Coloring all informations in the console

## Example

```JS

import ColoringConsole from './ColoringConsole';

const custom = new ColoringConsole;

const error = new ColoringConsole('error');

error.setBodyStyle({ color: 'red', size: '20px' });

console.log('Regular log..');

custom.log('Custom: Hello there!');

error.log('Custom Error: Something bad happened!');

```