##### List all connected displays
```
xrandr --listmonitors
```

##### List all connected displays with technical details
```
xrandr --current
```

##### Set brightness (10%) to a connected screen display [LDS-1 refers to the display device]
```
xrandr --output LDS-1 --brightness .10
```

##### Set brightness (100%) to a connected screen display [LDS-1 refers to the display device]
```
xrandr --output LDS-1 --brightness 1.0
```

##### Turn off the main laptop screen display [LDS-1 refers to the display device]
```
xrandr --output LDS-1 --off
```

##### Reset settings to a connected screen display [LDS-1 refers to the display device]
```
xrandr --output LDS-1 --auto
```

If you mistakenly set brightness (0%) for all displays, there will be no problem to set brightness back again.
