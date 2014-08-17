## which [![GoDoc](https://godoc.org/github.com/rjeczalik/which?status.png)](https://godoc.org/github.com/rjeczalik/which) [![Build Status](https://travis-ci.org/rjeczalik/which.png?branch=master)](https://travis-ci.org/rjeczalik/which "linux_amd64") [![Build Status](https://travis-ci.org/rjeczalik/which.png?branch=osx)](https://travis-ci.org/rjeczalik/which "darwin_amd64") [![Build status](https://ci.appveyor.com/api/projects/status/t97eqlnkpbb7chxx)](https://ci.appveyor.com/project/rjeczalik/which "windows_amd64") [![Coverage Status](https://coveralls.io/repos/rjeczalik/which/badge.png?branch=master)](https://coveralls.io/r/rjeczalik/which?branch=master)

Package which shows the import path of Go executables.

*Installation*

```bash
~ $ go get -u github.com/rjeczalik/which
```

*Documentation*

[godoc.org/github.com/rjeczalik/which](https://godoc.org/github.com/rjeczalik/which)

## cmd/gowhich [![GoDoc](https://godoc.org/github.com/rjeczalik/which/cmd/gowhich?status.png)](https://godoc.org/github.com/rjeczalik/which/cmd/gowhich)

*Installation*

```bash
~ $ go get -u github.com/rjeczalik/which/cmd/gowhich
~ $ go install github.com/rjeczalik/which/cmd/gowhich
```

*Documentation*

[godoc.org/github.com/rjeczalik/which/cmd/gowhich](http://godoc.org/github.com/rjeczalik/which/cmd/gowhich)

*Example usage*

```bash
~ $ gowhich godoc
code.google.com/p/go.tools/cmd/godoc
```
```bash
~ $ gowhich ~/bin/godoc
code.google.com/p/go.tools/cmd/godoc
```

## cmd/gofile [![GoDoc](https://godoc.org/github.com/rjeczalik/which/cmd/gofile?status.png)](https://godoc.org/github.com/rjeczalik/which/cmd/gofile)

*Installation*

```bash
~ $ go get -u github.com/rjeczalik/which/cmd/gofile
~ $ go install github.com/rjeczalik/which/cmd/gofile
```

*Documentation*

[godoc.org/github.com/rjeczalik/which/cmd/gofile](http://godoc.org/github.com/rjeczalik/which/cmd/gofile)

*Example usage*

```bash
~ $ gofile godoc
darwin_amd64
```
```bash
~ $ gofile ~/bin/godoc
darwin_amd64
```
