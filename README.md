# jongilm.jgInsertSignature

## Insert Date Time
Insert Signature of the form // <Name> <DateTimeStamp>

Feel free to choose any keybinding that suits. I recommend: Ctl+Alt+D

e.g. Add the following to keybindings.json:

[
    ...
    {
        "key": "alt+a",
        "command": "extension.jgInsertTag",
        "when": "editorFocus"
    },
    {
        "key": "ctrl+shift+d",
       "command": "extension.jgInsertSignature",
       "when": "editorFocus"
    },
    ...
]

## Installation
> Ctrl + Shift + I
> ext install jongilm.jgInsertSignature

**Enjoy!**
