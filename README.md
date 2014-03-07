
ObjcTask

API compatible (of the methods it supports) replacement for NSTask.

Useful if you need to tinker with the internals of a task e.g. adding code between the fork() and exec() calls. I'd only recommend using it if you need to do something you can't do with NSTask.

The callsystem.[hc] files are from the Io language project and were written by someone else. I just wrote the Objective-c wrapper for it.
