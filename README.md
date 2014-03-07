
ObjcTask

I created this because I wanted to be able to add behavior between the fork() and exec() calls done by NSTask. It's API compatible with NSTask (of the methods it supports) so most projects should be able to drop it in as a replacement without changing code. I'd only recommend using it if you need to do something you can't do with NSTask.

The callsystem.[hc] files are from the Io language project and were written by someone else. I just wrote the Objective-c wrapper for it.

Hope you find this code useful,
Steve