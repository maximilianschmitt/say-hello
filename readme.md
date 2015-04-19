# say-hello

This is a little demo project to show off how you can make your io.js command line apps work seemlessly on node.js with [Babel](http://babeljs.io/). [Check out the original article here](https://gist.github.com/maximilianschmitt/8ef57cb679fbf764b108).

## Installation

```
$ git clone https://github.com/maximilianschmitt/say-hello.git
$ cd say-hello
$ npm install
$ npm link
```

## Usage

```
$ say-hello
```

## Demo

```
$ node -v
v0.12.2
$ say-hello
Hello node.js
$ n io latest
$ node -v
v1.7.1
$ say-hello
Hello io.js
```