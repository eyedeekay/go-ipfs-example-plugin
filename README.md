# go-ipfs-example-plugin

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](http://ipn.io)
[![](https://img.shields.io/badge/project-IPFS-blue.svg?style=flat-square)](http://ipfs.io/)
[![](https://img.shields.io/badge/freenode-%23ipfs-blue.svg?style=flat-square)](http://webchat.freenode.net/?channels=%23ipfs)
[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
[![GoDoc](https://godoc.org/github.com/ipfs/go-ipfs-example-plugin?status.svg)](https://godoc.org/github.com/ipfs/go-ipfs-example-plugin)

> example plugin for go-ipfs

This repository contains a set of example go-ipfs plugins, demonstrating how to integrate external plugins into go-ipfs.

Packages:

* delaystore: an example datastore plugin that wraps an inner datastore in a "delayed" datastore.

**NOTE:** Plugins only work on Linux and MacOS at the moment. You can track the progress of this issue here: https://github.com/golang/go/issues/19282

## Building and Installing

Go-IPFS uses [gx](https://github.com/whyrusleeping/gx) as it's package manager. While most packages related to go-ipfs can be used without `gx`, packages that directly *depend* on go-ipfs (including this one) cannot.

If you don't have `gx`, install it with `make gx` (make sure that `$GOPATH/bin` is in your `$PATH`).

You can *build* the example plugin by running `make build`. You can then install it into your local IPFS repo by running `make install`.

**NOTE:** This plugin exists as an *example* and a starting point for new plugins. It isn't particularly useful by itself.

## Contribute

Feel free to join in. All welcome. Open an [issue](https://github.com/ipfs/go-ipfs-example-plugin/issues)!

This repository falls under the IPFS [Code of Conduct](https://github.com/ipfs/community/blob/master/code-of-conduct.md).

### Want to hack on IPFS?

[![](https://cdn.rawgit.com/jbenet/contribute-ipfs-gif/master/img/contribute.gif)](https://github.com/ipfs/community/blob/master/contributing.md)

## License

MIT
