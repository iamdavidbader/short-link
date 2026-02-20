# Short Link

A small tool for bridging the gap between analog and digital notes.

The problem is, sometimes I want to reference to a digital place in my analog notes.
However, digital urls are usually quite long.
Instead, I use a short id which references the long url.

I created a simple script that stores urls in separate files which are named by a unique 4 digit alpha numerical id.

The usage is as follows:

```
short-link add <url> # prints id
short-link list # prints all entries (id  url)
short-link get <id> # prints link
short-link delete <id> # prints id
short-link update <id> <url>
```
