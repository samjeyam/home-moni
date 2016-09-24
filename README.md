Home Monitor App - Go App
=========================

# pre-requsite

## clone

```
git clone https://github.com/samjeyam/home-moni.git $GOPATH/src/github.com
```


## get revel framework
[revel](http://revel.github.io/)

```bash
$ go get github.com/revel/revel
```
Ensure the $GOPATH/bin directory is in your PATH 


Verify that it works:

```bash
$ revel help
```


## sqlite Installation

This app uses [go-sqlite3](https://github.com/mattn/go-sqlite3) database driver (which wraps the native C library). 


### To install on OSX:

1. Install [Homebrew](http://mxcl.github.com/homebrew/) if you don't already have it.
2. Install pkg-config and sqlite3:

~~~
$ brew install pkgconfig sqlite3
~~~

### To install on Ubuntu:

	$ sudo apt-get install sqlite3 libsqlite3-dev


# Run the app	

Once you have SQLite installed, it will be possible to run the  app:

$ revel run github.com/home-moni


