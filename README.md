# fwatch
![tests](https://github.com/msAlcantara/fwatch/workflows/tests/badge.svg) ![GitHub release (latest by date)](https://img.shields.io/github/v/release/msAlcantara/fwatch?style=plastic) ![GitHub](https://img.shields.io/github/license/msAlcantara/fwatch?style=plastic)

Utility to execute command when file changes

## Usage

Watch current directory and execute ls when some file change:

```bash
$ fwatch ls
```

Watch custom directory:

```bash
$ fwatch -dir /path/to/directory ls
```

Ignore pattern files:

```bash
fwatch -ignore "*_test.go,*.test.js" ls
```

Execute command to only specific pattern:

```bash
$ fwatch -pattern "*.go,**.js*" ls
```

Verbose mode:

```
$ fwatch -V ls
```

Help:

```bash
fwatch -h
```


## License
[MIT](https://github.com/msAlcantara/fwatch/blob/master/LICENSE)
