# cmus 

## What is cmus?

cmus is a small, fast and powerful console music player for Unix-like operating systems.

[cmus.github.io](https://cmus.github.io)

## How to use this image

```
docker run -it -v $HOME/music:/home/user/music:ro \
  -v $HOME/.cmus:/home/user/.cmus \
  -v /dev/snd:/dev/snd --privileged \ 
  -v $HOME/.asoundrc:/home/user/.asoundrc cmus
```
