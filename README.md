# serve-demock

A [Demock](https://github.com/atesgoral/demock)-enabled simple HTTP server

## Installation

```
npm install -g serve-demock
```

## Usage


```
serve-demock [options] [root directory]

Options:

-h, --help              output usage information
-V, --version           output the version number
-j, --json-path <path>  specify the relative path to mock JSON data [/]
-p, --port <port>       specify the port [3000]
-i, --ignore-mime       ignore MIME type
```

By default, the current working directory is served and all JSON files are filtered through Demock.
