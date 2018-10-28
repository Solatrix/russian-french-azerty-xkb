# Russian-French-azerty-xkb

**French-based azerty keyboard layout with Russian letters' mapping**

This layout is adapted from tradition french-azerty keyboard layout, with Russian cyrillic letters mapping. 
Feel free to submit any improvement & suggestion for review.

At the moment, the layout looks like this : 
![Image of Layout](https://image.ibb.co/k6G6Aq/Russian-azerty-layout.png)

Palatalisation phenomenon is represented with combination of AltGr + Letter
i.e : `с + AltGR = ш`

## Further implementations may encapsulate :

- Prior to 1917 orthograph reform letters (mainly ѣ, and и с точкой "і")
- Better mapping of punctuation characters
- Mapping other slavic languages cyrillic letters such as Serbian soft l, and n
- Adding diacritics possibilities (diaerisis or tréma) 
  at the moment, circumflex accent (^) can be used to write stress down (ударе́ние)
  
  
  ## Installation guidelines
  I'm personally a user of SolusOS, but the proceedings are essentially the same for Debian-based distros, at least to the best of my knowledge (Feel free to add instructions for other distros in there).
  
  *Editing system files is not recommended for newbies, be careful and please backup original files before doing anything stupid*
  
  In *sudo* mode, you have to edit your : 
    `/usr/share/X11/xkb/symbols/ru`
  File to add the content of the one available on this repo
  You have to add an entry in : 
    `/usr/share/X11/xkb/rules/evdev.xml`
 You should then be able to add your keyboard layout in the input parameters of your OS
  
  ## Highly recommended documentation to make up your own layout
 
 - [Karol Stasiak's Blog](https://karols.github.io/blog/2013/11/18/creating-custom-keyboard-layouts-for-linux/)
 - [LSDevLinux Wiki](http://linux.lsdev.sil.org/wiki/index.php/Building_an_XKB_Keyboard)
 - [Ubuntu's official documentation on customizing keyboard layouts](https://help.ubuntu.com/community/Custom%20keyboard%20layout%20definitions?action=show&redirect=Howto%3A+Custom+keyboard+layout+definitions)
 
### Special thanks to 
[Alexriss](https://github.com/alexriss) for his [Keyboard converter](https://github.com/alexriss/keyboard-layout-converter) that basically enabled me to convert my old windows klc file to make it compatible with Linux distros
