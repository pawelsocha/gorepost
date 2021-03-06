gorepost
========
[![Build Status](https://api.travis-ci.org/arachnist/gorepost.svg?branch=master)](https://travis-ci.org/arachnist/gorepost)
[![GoDoc](https://godoc.org/github.com/arachnist/gorepost?status.svg)](https://godoc.org/github.com/arachnist/gorepost)
[![Coverage Status](https://coveralls.io/repos/arachnist/gorepost/badge.svg?branch=master&service=github)](https://coveralls.io/github/arachnist/gorepost?branch=master)

Gorepost implements an overengineered IRC bot.

The name gorepost stands for "go rewrite of repost". Repost was my older IRC bot
written in Ruby. The main features are:

 * Gracefully handles connection errors and reconnects.
 * Handles connections to multiple IRC networks and connects to a random IRC
   server from provided list
 * Dynamic configuration inspired by [Puppetlabs Hiera](https://github.com/puppetlabs/hiera).
   Currently implements only one backend (JSON) and does not support slice
   merging across configuration tiers, but it's getting there.

## License
MIT License. See the LICENSE file for details.

