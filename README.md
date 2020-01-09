# wttr.in Background
add wttr.in to image and set it as background in **Ubuntu OS**!

`NOTE : this script tested in Ubuntu Mate 18.04, for other linux distribution can experiment with this script`

**Requirement :** `curl`
if you don't have it, install it from dist repository `sudo apt install curl` (Ubuntu)

This bash script used to add wttr.in to random image in `$HOME/Pictures/backgrounds/rands` directory and set selected one image as desktop background.

## Change Random Image Directory
Change folder path in line `4` to your desired path

## Change wttr.in City/Location
Change **city** in `curl` link at line `16`. For example `"wttr.in/London_tqp0_lang=en.png"`

## Run Script
Give this script execute permission with `chmod +x wttr-randbgr`. Run this script with `./wttr-randbgr`
