# Jotack :computer:
A flat [conky](https://github.com/brndnmtthws/conky) theme for your desktop. I designed it in order to have a general overview of system resources with a clear look and no dependencies from other packages or software (like weather APIs, curl, lua...). This way, it is ready to be used “as is” without much hassle and post-configurations.

#### Installation

* Install conky using the package manager of your Linux distribution. If using **RHEL** based distro, be sure to have **EPEL** repositories enabled:

        # Debian & based
        apt-get install conky
        # RHEL & based
        yum install conky
        # OpenSUSE
        zypper in conky
        # Arch Linux
        pacman -S conky

* The theme uses **DejaVu Sans** and **Calibri** fonts.
* Just move or copy the content of the corresponding .conkyrc of this respository into your ~/.conkyrc file. If the file doesn't exist after installing conky, just create it.

#### Modifications

Certain sections of the conky configurations files I uploaded to the repository are commented. For example, the temperature of the CPU cores. Feel free to activate those monitorings or modify as you want or even add the features you need.

#### Sample

The theme comes in versions dark and light:

![Alt text](/samples/jotack_dark.png?raw=true "Dark Jotack theme")
![Alt text](/samples/jotack_light.png?raw=true "Light Jotack theme")

Enjoy! :smiley:
