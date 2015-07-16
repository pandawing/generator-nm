# <%= moduleName %>

[![Build Status][travis-image]][travis-url] [![Build Status][appveyor-image]][appveyor-url]

> My spectacular module


## Install

```
$ npm install --save <%= moduleName %>
```


## Usage

```js
var <%= camelModuleName %> = require('<%= moduleName %>');

<%= camelModuleName %>('unicorns');
//=> unicorns & rainbows
```
<% if (cli) { %>

## CLI

```
$ npm install --global <%= moduleName %>
```
```
$ <%= moduleName %> --help

  Usage
    <%= moduleName %> [input]

  Example
    <%= moduleName %>
    unicorns & rainbows

    <%= moduleName %> ponies
    ponies & rainbows

  Options
    --foo  Lorem ipsum. Default: false
```
<% } %>

## API

### <%= camelModuleName %>(input, [options])

#### input

*Required*  
Type: `string`

Lorem ipsum.

#### options

##### foo

Type: `boolean`  
Default: `false`

Lorem ipsum.


## License

MIT © [<%= name %>](<%= website %>)

[travis-url]: https://travis-ci.org/<%= githubUsername %>/<%= moduleName %>
[travis-image]: https://travis-ci.org/<%= githubUsername %>/<%= moduleName %>.svg?branch=master
[appveyor-url]: https://ci.appveyor.com/project/<%= githubUsername %>/<%= moduleName %>/branch/master
[appveyor-image]: https://ci.appveyor.com/api/projects/status/YOUR_KEY/branch/master?svg=true
