## Fix multi monitor greeters screen

Set up screens in gui settings and then

```
cp ~/.config/monitors.xml /var/lib/gdm3/.config
chown gdm:gdm /var/lib/gdm/.config/monitors.xml
```
