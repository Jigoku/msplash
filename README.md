# msplash
A simple init script that allows you to use a looped video as a bootsplash

### Notes
* Requires MPlayer
* Only tested on Slackware Linux so far
* You will have to supress boot messages manually

### How to use
* Adjust $MSPLASHVIDEO to contain the path to your video file
```
MSPLASHVIDEO=/boot/loading.mp4
```

* Add to the beginning of /etc/rc.d/rc.S
``` 
/etc/rc.d/rc.msplash start
```

* Place at the end of /etc/rc.d/rc.local
```
/etc/rc.d/rc.msplash stop
```

