# Openpnp-klipper


https://www.reddit.com/r/klippers/comments/16cflhf/klipper_pickplace_machine/


This command makes bi-directional communication work. It  should now work more or less flawless
```bash
sudo socat TCP-LISTEN:23,reuseaddr,fork OPEN:/dev/pts/0,append
```
