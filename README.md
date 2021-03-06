# Pyre
Terminal fire

![pyre](example.gif)

### What
A fire animation for the terminal, with support for 256 colors.

### Install
```
python setup.py install
```

### Requires
`ncurses`

### Run
```
python pyre.py
```
If installed:
```
pyre
```

### Controls
Keys  | Actions
----- | -------
<kbd>q</kbd> or <kbd>Q</kbd> or <kbd>Esc</kbd> | quit
<kbd>p</kbd> or <kbd>P</kbd> | pause
<kbd>v</kbd> or <kbd>V</kbd> | toggle verbose output
<kbd>c</kbd> or <kbd>C</kbd> | change colors (random)
<kbd>t</kbd> or <kbd>T</kbd> | change colors over time
<kbd>s</kbd> or <kbd>S</kbd> | smoothly change colors over time
<kbd>i</kbd> or <kbd>I</kbd> | toggle auto-intensity
<kbd>f</kbd> or <kbd>F</kbd> | toggle fluctuate intensity
<kbd>,</kbd> or <kbd><</kbd> | decrease intensity
<kbd>.</kbd> or <kbd>></kbd> | increase intensity
<kbd>-</kbd> or <kbd>_</kbd> | decrease update delay
<kbd>=</kbd> or <kbd>+</kbd> | increase update delay

### Support
- [x] Works on Linux completely

- [x] Works on OSX completely

- [ ] Windows not supported

### Credit
Inspired by:
https://gist.github.com/cursed255/011c56ce40df0baf1d50
