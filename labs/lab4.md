#Lab 4

The locations of the bug reports I sent in are as follows:

https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=207504
https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=207505

####What Was Changed

The only things that were really changed were fixing a broken tag (it was written as os; instead of &os;, which caused FreeBSD to not show up properly), and fixing the appearance of an error message that would make more sense to be separated out from the text, rather than mixed amongst the plain text.

####On Keeping Good Documentation

While all I changed were small typos in the code, imagine if someone mistook the os; text error to be some hidden part of the system that they thought didn't exist. Of course, not many would, but I imagine that isn't an uncommon typo, so it could accidentally "confirm" the existence of something that doesn't really exist. This kind of recurring problem is why it's necessary to keep good documentation. Users need good documentation in order to completely and fully understand the ins and outs of the software they are using, and if some part is wrong or not fully explained, the user will be trying to operate the code without proper information and will end up confused as to why it isn't working. Therefore, I have to also keep a close eye on what I do in the future, and when I share my code, I need to make sure that it is properly documented so that there are very few issues on the user's end.