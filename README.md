# yamaha_ag08_loopback
Out of the box, Pipewire doesn't really know what to do with all the channels on the Yamaha AG08 Mixer. This set of loopback device configs should give you more or less what you'd see in Windows.
## Setup
Set your AG08's profile to "Pro Audio" and drop these into `~/.config/pipewire/pipewire.conf.d/`\
Then, `systemctl --user restart pipewire wireplumber`
## Additional Notes
There are a few capture_AUX channels I didn't use because I didn't find them useful enough to have cluttering up my device list. They are listed here.\
AUX6 - Channel 1, no fader control\
AUX7 - Channel 2, no fader control\
AUX8 AUX9 - Channel 3/4 only, no fader control\
AUX10 AUX11 - Channel 5/6 only, no fader control\
AUX12 AUX13 - Channel 7/8 only, no fader control
