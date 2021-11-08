### Formatting and re-partitioning a new drive on Ubuntu
https://www.tecklyfe.com/how-to-partition-format-and-mount-a-disk-on-ubuntu-20-04/

### Setting up automatic disk health checks with email notifications on failure
#### go to Server section
https://help.ubuntu.com/community/Smartmontools

### xRandR auto-connect when HDMI is plugged in on laptop
Before plugged in for the first time:
`autorandr --save mobile`

When plugged in for the first time (for laptop display eDP-1 and external display HDMI-2)
`xrandr --output eDP-1 --off --output HDMI-2 --auto --primary`
`autorandr --save docked`


### Reinstall Android app that you deleted
```
adb shell
$ pm install-existing --user 0 <pkg_name>
```
