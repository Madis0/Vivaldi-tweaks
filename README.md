# CSS tweaks for Vivaldi

A list of tweaks I have made for the [Vivaldi browser](https://vivaldi.net). Some tweaks may not be compatible with each other so test, read comments and adjust code as needed. The tweaks are free to use, modify and republish, unless written otherwise per-file.

For more tweaks, check out [official forum](https://forum.vivaldi.net/category/52/modifications). I also co-create [tweaks for Firefox](https://github.com/Timvde/UserChrome-Tweaks).

### How to use the tweaks

1. Open `vivaldi://about`
2. Open the Executable Path in your file browser without the last part (such as `/vivaldi.exe`)
3. Click on *(version number)* -> **resources** -> **vivaldi**
4. Close Vivaldi
5. Open `browser.html` with a text editor with administrator permissions
6. Add `<link rel="stylesheet" href="style/custom.css" />` after `<link rel="stylesheet" href="style/common.css" />`
7. Open **style** and create a file `custom.css` with a text editor with administrator permissions
8. Copy any code snippets from the folder **CSS** to the file, save the file
9. Start Vivaldi, enjoy!

You may need to follow the tutorial again after Vivaldi updates.

### How to inspect Vivaldi's UI

1. Go to `vivaldi://flags`
2. Enable **#debug-packed-apps**
3. Restart Vivaldi
4. Right click on any UI element, select Inspect
