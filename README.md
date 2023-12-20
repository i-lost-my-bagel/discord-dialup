# discord-dialup
My systemd units for a simple FSK dial up connection over a Discord voice call.

Relies on [minimodem](https://github.com/kamalmostafa/minimodem)

Make 2 pulseaudio/pipewire null sinks and assign the inputs and output of minimodem in discord to them in a way so that each side can't hear the sound it outputs and so you don't have to hear the modem screaming sounds
