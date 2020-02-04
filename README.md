# NoMoreSound
# Tired of that annoying popping sound when volume is changed?

Mapped keys for silent volume changing in Ubuntu are ALT + VOL UP/DOWN

# Replace OEM sound with a silent one (1s)

1) Save the .oga filee wherever you want
2) Make a copy of the original sound:
# mv /usr/share/sounds/freedesktop/stereo/audio-volume-change.oga /usr/share/sounds/freedesktop/stereo/audio-volume-change.oga.backup
3) Just copy the new sound over
# sudo cp %yourpath%/silent.ogg /usr/share/sounds/freedesktop/stereo/audio-volume-change.oga
4) Reboot
