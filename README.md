### Sublime Text 4 Theme in Visual Studio Code!

<p align="center"><img width="800px" src="https://i.ibb.co/n6KG8CZ/Sublime-Text-4-Theme.png"></p>
<p align="center">

## Installing information

Theme install

### Installation

Quick Open:
Windows: Ctrl + P
macOS: ⌘ + P
Linux: Ctrl + P

Paste the following command and press `Enter`:

```shell
ext install sublime-text-4-theme
```

...pick the theme

## Theme activation

Quick Open:
Windows: Ctrl + Shift + P
macOS: Shift + P
Linux: Ctrl + Shift + P

Type `theme`, choose `Preferences: Color Theme`, and select Sublime Text 4 Theme

### Overriding the colors

**Editor colors**

```js
"editor.tokenColorCustomizations": {
    "[Sublime Text 4 Theme]": {
        "textMateRules": [
            {
                "scope": "comment",
                "settings": {
                     "foreground": "#74705D",
                }
            },
        ]
    },
},
```

**Theme colors**

"workbench.colorCustomizations": {
"[Sublime Text 4 Theme]": {
"editor.selectionBackground": "#ff0000",
}
},

## Recommended settings for complete Sublime Text 4 experience

```js
{
    // Changes to like Sublime Text 4 Theme now even more
    "editor.letterSpacing": 0.55,
    "editor.lineHeight": 18,
    "workbench.colorCustomizations": {
        "editorCursor.foreground":"#f9ae58"
    }
}
```

# sublime-text-4-theme
