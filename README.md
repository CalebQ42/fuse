github.com/CalebQ42/fuse -- Filesystems in Go
===================================

This is a fork of http://bazil.org/fuse , for performance 
and to merge all good pull requests.

`github.com/CalebQ42/fuse` is a Go library for writing FUSE userspace
filesystems.

It is a from-scratch implementation of the kernel-userspace
communication protocol, and does not use the C library from the
project called FUSE. `github.com/CalebQ42/fuse` embraces Go fully for safety and
ease of programming.

Here’s how to get going:

    go get github.com/CalebQ42/fuse

Website: http://github.com/CalebQ42/fuse/

Github repository: https://github.com/bazil/fuse

API docs: http://godoc.org/github.com/CalebQ42/fuse

Our thanks to Russ Cox for his fuse library, which this project is
based on.
