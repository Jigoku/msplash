# msplash
A simple init script that allows you to use a looped video as a bootsplash

### Notes
* Requires MPlayer
* Only tested on Slackware Linux so far
* You will have to supress boot messages manually

### How to use
* Launch the script from /etc/rc.d/rc.S
``` 
/etc/rc.d/rc.msplash start
```

* End the script from /etc/rc.d/rc.local
```
/etc/rc.d/rc.msplash stop
```

