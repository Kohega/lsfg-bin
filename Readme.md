# LSFG Executables

Executables to enable [lsfg-vk](https://github.com/PancakeTAS/lsfg-vk) via launch options. 


## Installation
Write these commands in your terminal.

    git clone https://github.com/Kohega/lsfg-bin
	chmod +x lsfg-bin/lsfg*
	mv lsfg-bin/lsfg* $HOME/.local/bin

 ## Default behavior
 My settings for `lsfg` is :

    Multiplier = 2
    Performance mode = YES
    Flow Scale = Default
    Experimental Present Mode = VSync

My settings for `lsfgx3` is :

    Multiplier = 3
    Performance mode = YES
    Flow Scale = Default
    Experimental Present Mode = VSync

This is what my hardware supports, but you're free to edit them accordingly to your hardware.
# Usage

It's up to you to edit the `lsfg` to your prefered settings

## Steam

Add this command to the launch arguments.

    lsfg %command%    
 OR
 
    lsfgx3 %command%

![enter image description here](https://i.imgur.com/sf6bNj5.png)

## Flatpak apps in Steam

Add this command to the TARGET.

    lsfg-flatpak %command%    
 OR
 
    lsfgx3-flatpak %command%


