# Linux-Commands

how much space is used?
```
df -h --total
```


where biggest files/directories on my system are stored?

```
du -a | sort -nr | head
```
ref: https://askubuntu.com/questions/2045/how-to-determine-where-biggest-files-directories-on-my-system-are-stored


To list the top 10 largest files from the current directory: 
```
du . | sort -nr | head -n10
```

To list the largest directories from the current directory:
```
du -s * | sort -nr | head -n10
```

ref: https://unix.stackexchange.com/questions/37221/finding-files-that-use-the-most-disk-space
