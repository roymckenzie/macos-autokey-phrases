# macOS phrases for AutoKey

Use macOS-style keyboard shortcuts for:

| Command | Shortcut | Window Filter
|---|:---:|---|
Bold | ⌘+b
Comment line | ⌘+/
Copy | ⌘+c
Cut | ⌘+x
Find | ⌘+f 
Firefox New Private Window | <shift>+⌘+n | Navigator.Firefox
Firefox Refresh | ⌘+r | Navigator.Firefox
Italicize | ⌘+i
Move left and select by word | <alt>+<shift>+<left>
Move left by word | <alt>+<left>
Move right and select by word | <alt>+<shift>+<right>
Move right by word | <alt>+<right>
Move to beginning of line | ⌘+<left>
Move to end of line | ⌘+<right>
New tab | ⌘+t
New window | ⌘+n
Paste | ⌘+v
Redo | <shift>+⌘+z
Save | ⌘+s
Select all | ⌘+a
Select to beginning of line | <shift>+⌘+<left>
Select to end of line | <shift>+⌘+<right>
Send email (elementary Mail) | <shift>+⌘+d | pantheon-mail.Pantheon-mail
Switch tab (Firefox) | <alt>+<tab> | Navigator.Firefox
Undo | ⌘+z

## Installation

Install [AutoKey](https://github.com/autokey/autokey) from AppCenter (elementary OS) or

```bash 
$ sudo apt install autokey-gtk
```

Clone repository and copy `My Phrases` folder to `~/.config/autokey/data`.

```bash
$ git clone git@github.com:roymckenzie/macos-autokey-phrases.git
$ cp -r My\ Phrases/ ~/.config/autokey/data/
```

Enjoy!

### Contribute

Have a macOS-style shortcut that is missing from this list? Make a pull request.
