```
                                                       ▀▀▀▀▀     ▀▀▀▀▀          ▀▀█▀▀
                                                       ▄▀▀▀▄  ▄  ▄▀▀▀▄  ▄  ▄▀▀▀▄  █  ▄▀▀▀▄
                                                       █   █  █  █   █  █  █   █  █  █   █
                                                        ▀▀▀   █   ▀▀▀   █   ▀▀▀   ▀   ▀▀▀
                                                              █      ▄▄▄█▄▄▄    █   █  
                                                              ▀      █  █  █     █▄█
                                                            ▀▀▀▀▀    █  █  █      ▀
                                                                     ▀  ▀  ▀
▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄
       
```
# TOTEM split keyboard

TOTEM is 34 keys column-staggered split keyboard made by @geigeigeist. It uses the Seeed XIAO RP2040.

You can use this command to compile the firmware
`qmk compile -kb totem -km default`

For vial:

`qmk compile -kb totem -km vial --target uf2-split-left --parallel 0`

`qmk compile -kb totem -km vial --target uf2-split-right --parallel 0`

First time run:

`make totem:vial`
