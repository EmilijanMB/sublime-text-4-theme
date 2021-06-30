### Sublime Text 4 Theme in Visual Studio Code! New default dark theme from Sublime Text 4!

<p align="center"><img width="800px" src="https://i.ibb.co/dgvrYCz/sublime-text-4-theme.jpg" alt="sublime-text-4-theme"></p>
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
ext install EmilijanMB.sublime-text-4-theme
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
    
    "breadcrumbs.enabled": false,
    "editor.letterSpacing": 0.55,
    "editor.lineHeight": 18,
    "window.menuBarVisibility": "compact"
}
```

# sublime-text-4-theme
