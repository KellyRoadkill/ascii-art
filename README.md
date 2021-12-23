# ASCII/ANSI images for Neofetch and beyond

* Install https://github.com/dylanaraps/neofetch/
* Download `Neofetch/*.txt` files from this repo
* Run Neofetch with arguments (see below)

  *or*

* Modify your `~/.config/neofetch/config.conf` to make changes permanent

### IBM ThinkPad classic logo (vertical) ###
    neofetch --ascii --source "/path/to/ibm-tp-v.txt" --ascii_colors '7' '1' '2' '4'
![Neofetch with IBM ThinkPad logo (vertical)](https://github.com/roadkell/ascii-art/blob/main/screenshots/ibm-tp-v-neofetch.png?raw=true)

### IBM ThinkPad classic logo (horizontal) ###
    neofetch --ascii --source "/path/to/ibm-tp-h.txt" --ascii_colors '7' '1' '2' '4'
![Neofetch with IBM ThinkPad logo (horizontal)](https://github.com/roadkell/ascii-art/blob/main/screenshots/ibm-tp-h-neofetch.png?raw=true)

### Bonus version: trans rights! 🏳️‍⚧️ ###
    neofetch --ascii --source "/path/to/ibm-transpad-v.txt" --ascii_colors '15' '14' '9'
    neofetch --ascii --source "/path/to/ibm-transpad-h.txt" --ascii_colors '15' '14' '9'
![IBM TransPad logo (vertical)](https://github.com/roadkell/ascii-art/blob/main/screenshots/ibm-transpad-v.png?raw=true)
![IBM TransPad logo (horizontal)](https://github.com/roadkell/ascii-art/blob/main/screenshots/ibm-transpad-h.png?raw=true)


* There are some Unicode symbols in use beyond the classic 8-bit ASCII code page (notably, [Block Elements](https://en.wikipedia.org/wiki/Block_Elements) and [Symbols for Legacy Computing](https://en.wikipedia.org/wiki/Symbols_for_Legacy_Computing)), so make sure your terminal and font support Unicode (I use [kitty](https://github.com/kovidgoyal/kitty/) with [MesloLGS NF font](https://github.com/romkatv/powerlevel10k#meslo-nerd-font-patched-for-powerlevel10k)).
* These are not proper ANSI images, they use [Neofetch ASCII file format](https://github.com/dylanaraps/neofetch/wiki/Custom-Ascii-art-file-format) which is quite color-limited. This will change when Neofetch [implements](https://github.com/dylanaraps/neofetch/issues/1699) [ANSI escape codes](https://en.wikipedia.org/wiki/ANSI_escape_code#24-bit).
* Alt versions of logos, as well as plain ASCII, are also available. Enjoy!


Disclaimer: I am not affiliated with IBM or Lenovo. All trademarks, logos and brand names are the property of their respective owners. Use of these names, trademarks and brands does not imply endorsement.
