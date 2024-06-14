# copypath
A POSIX shell client to copy the path of the selected file into the system clipboard using pbcopy.

# Installation
Installation of this script is really simple. All you need to do is to copy the (tldr script)[https://raw.githubusercontent.com/avi1989/copypath/master/copypath] into a folder in your system PATH.

```
   curl -o /opt/bin/copypath https://raw.githubusercontent.com/avi1989/copypath/master/copypath
   chmod +` /opt/bin/copypath
```

# Dependencies
copypath uses pbcopy to copy the output into memory.