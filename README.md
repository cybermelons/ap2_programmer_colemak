# Overview

Upload here and configure: https://config.qmk.fm/#/annepro2/c18/LAYOUT_60_ansi

```
Fn2 + Z -> Default QWERTY Layout Layer
Fn2 + X -> Toggle [Programmer Colemak](https://github.com/aru-py/programmer-colemak) Layer
Fn2 + C -> Toggle [Colemak-DH Layer](https://colemakmods.github.io/mod-dh/)
Fn2 + V -> Toggle [Programmer Dvorak](https://www.kaufmann.no/roland/dvorak/) Layer
```

## QMK

QMK keyboard layout found as a json file.

## KTouch

You can train using KTouch with the custom layout and lessons I created. these
are found in `ktouch/ktouch_lessons.xml` and `ktouch/us(colemak-programmer).xml`

Dictionary taken from [12dicts](http://wordlist.aspell.net/dicts/).
Lesson generator included is from [here](https://github.com/simgunz/ktouch-lesson-generator).

The lesson was generated with the command

```
ktouch-lesson-generator ./ktouch/colemak-programmer-lessons-schema.txt ktouch/12dict.txt
```
