# ttymidi
ttymidi with SysEx support (for MT-32)

I modified ttymidi in order to be able to process SysEx messages. This is crucial for some applications (like using Munt). I only implemented in one direction for now (Midi serial -> ALSA) as that is the only thing important for Munt.

The code is based on sixeight7's code (https://github.com/sixeight7/ttymidi). His code unfortunately didn't work correctly.
