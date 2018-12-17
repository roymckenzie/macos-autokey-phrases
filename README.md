# macOS phrases for AutoKey

Use macOS-style keyboard shortcuts for:

| Command | Shortcut | Window Filter
|---|:---:|---|
Bold | ⌘+b
Comment line | ⌘+/
Copy | ⌘+c
Cut | ⌘+xF
Find | ⌘+f 
Firefox New Private Window | ⇧+⌘+n | Navigator.Firefox
Firefox Refresh | ⌘+r | Navigator.Firefox
Italicize | ⌘+i
Move left and select by word | ⌥+⇧+←
Move left by word | ⌥+←
Move right and select by word | ⌥+⇧+→
Move right by word | ⌥+→
Move to beginning of line | ⌘+←
Move to end of line | ⌘+→
New tab | ⌘+t
New window | ⌘+n
Paste | ⌘+v
Redo | ⇧+⌘+z
Save | ⌘+s
Select all | ⌘+a
Select to beginning of line | ⇧+⌘+←
Select to end of line | ⇧+⌘+→
Send email (elementary Mail) | ⇧+⌘+d | pantheon-mail.Pantheon-mail
Switch tab (Firefox) | ⌥+⇥ | Navigator.Firefox
Undo | ⌘+z
Close Tabbed Window | ⌘+w
Close focused application| ⌘+q

## Installation

Install [AutoKey](https://github.com/autokey/autokey) from AppCenter (elementary OS) or

```bash 
$ sudo apt install autokey-gtk
```

Clone repository and copy `macOS` folder to `~/.config/autokey/data`.

```bash
$ git clone git@github.com:roymckenzie/macos-autokey-phrases.git
$ cp -r macOS/ ~/.config/autokey/data/
```

Enjoy!

### Contribute

Have a macOS-style shortcut that is missing from this list? Make a pull request.
