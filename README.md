# yamaha_ag08_loopback
Pipewire Loopback Device Configs for the Yamaha AG08 Mixer
## Instructions
Set your AG08's profile to "Pro Audio" and drop these in `~/.config/pipewire/pipewire.conf.d
Then, `systemctl --user restart pipewire wireplumber
## Additional Notes
There are a few capture_AUX channels I didn't use. They are listed here.
6 - Channel 1, bypasses fader
7 - Channel 2, bypasses fader
8+9 - Channel 3/4 only, bypasses fader
10+11 - Channel 5/6 only, bypasses fader
12+13 - Channel 7/8 only, bypasses fader
