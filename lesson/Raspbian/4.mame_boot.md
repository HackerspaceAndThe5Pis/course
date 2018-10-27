### Set Mame to load on boot
```sh
Edit /home/.profile
```
Add the following line at the end of the file:
```sh
if [ -z "$DISPLAY" ] && [ -n "$XDG_VTNR" ] && [ "$XDG_VTNR" -eq 1 ]; then
	cd /home/code/mame4all_pi
	./mame
fi
```