# The Ganesha Keyboard

The Ganesha is a keyboard inspired by and forked from the amazing Corne keyboard. After having built a number
of Corne KBs, I need something that has the number row. There are other forks like Lily58 (and further still, like
Sofle, Orbit etc) but they have certain features that I have a strong preference to remove (mirrored PCB, unutilized
component designations, dependence on Pro Micro etc).

## Major Design Goals
### User's POV
1. Split ortho-linear layout.
2. Have a dedicated numbers row.
3. No bigger than a standard print of Moby Dick when packed.
4. Enable USB-C without the added cost of an Elite-C board.
5. Per Key and ambient LEDs.

### Builder's POV
1. Enable factory assembly as much as possible (jlcpcb.com in my case)
2. Clean, self documenting PCB layout.
3. Compatible with low-profile switches and keycaps
4. Directly embedded atmega32u4
5. 4 layer PCB

## Dependencies
### KiCad libraries
You should clone https://github.com/foostan/kbd to get the symbol and footprint libraries used in these kicad projects.
1. Clone this repo and foostan/kbd
1. Install kicad.
1. Open ganesha.pro in Kicad.
1. Preferences > Manage Symbol Libraries
    1.  Hover over the folder looking icon below the table, it should say "Add existing table to library". 
    2.  Click that button.
    3.  Navigate to the symbol library located under kbd/kicad-symbols/
    4.  Add. 
1. Repeat the same process for footprint libraries.

## Starting Priorities
Calling out a few assumptions I will be starting with, but would like to expand when time permits.
1. Kailh Cherry MX hot swap sockets as switch anchors

## Why "Ganesha"?
Ganesha, in Hindu mythology, is the popular elephant headed deity whose images you may have seen. Aside from being the son 
of Lord Shiva, he is also the God of Wisdom and more pertinently, he is the scribe who penned down the great epic 
'Mahabharata' as sage Vyasa composed it.
