<b>Go 101</b> is a book focusing on Go syntax/semantics and all kinds of details.
The book also tries to help gophers understand Go deeply and thoroughly.

### Install And Update

Run

```
$ go get -u github.com/go101/go101
```

or

```
$ go get -u gitlab.com/go101/go101
```

to install and update ***Go 101***.

*(NOTE: if your last `go get -u` command run was before **May 5th, 2018**,
please run this command again to install the latest `go101` program.)*

### Run Locally

Add the path of the `bin` folder under `GOPATH`
into `PATH` environment variable to run `go101`.
The default value of the `GOPATH` environment variable
is the path of the `go` folder under the home directory.

```
$ go101
Server started:
   http://localhost:55555 (non-cached version)
   http://127.0.0.1:55555 (cached version)
```

The start page should be opened in a browser automatically.
If it is not opened, please visit http://localhost:55555.

### Some Notes

* The book is in beta phase now. Many articles still need correcting.
* Translations are welcome, but for the last note, it may not (but will soon) be the proper time to do so.
* Chinese translation version is maintained by myself ([@TapirLiu](https://twitter.com/tapirliu)).
* Please read [UPDATES.md](UPDATES.md) for update history.
