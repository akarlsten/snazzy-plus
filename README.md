<p align="center">
  <img src="https://github.com/akarlsten/snazzy-plus/raw/master/images/icon.png" width="150" height="150">
</p>

A VS Code theme based on [hyper-snazzy](https://github.com/sindresorhus/hyper-snazzy) and [vscode-snazzy-operator](https://github.com/aaronthomas/vscode-snazzy-operator).

Changes compared to Aaron Thomas version are:

- Theming for every part of the UI. If I missed anything let me know!
- A darker yellow color (taken from Dracula, i think) as the pale yellow in the original didn't appeal to me.
- Alternate version with **_italics_** for keywords like "this" and "class" for use with Operator/Dank Mono.
- Alternate **darker version** that I've started preferring on my brighter laptop screen.

Feel free to open a Github issue for any comments/suggestions.

## Snazzy Plus

![snazzy-plus-preview](https://github.com/akarlsten/snazzy-plus/raw/master/preview.png)

## Snazzy Plus - Darker

![snazzy-plus-dark-preview](https://github.com/akarlsten/snazzy-plus/raw/master/preview-dark.png)

## Italics

![snazzy-plus-dark-italics-preview](https://github.com/akarlsten/snazzy-plus/raw/master/preview-italics.png)

## Customizing

If you want to customize the theme and change a specific syntax color (for example, you may find that comments are too dark) you can do this inside your `settings.json` file for VS Code.

An example:
```
"editor.tokenColorCustomizations": {
    "[Snazzy Plus - Darker]": {
      "comments": "#aaa",
    },
  },
 ```
 
 You can also change UI elements in a similiar fashion:
 ```
"workbench.colorCustomizations": {
    "[Snazzy Plus - Darker]": {
      "sidebar.background": "#347890",
    },
  },
```

Intellisense should supply auto-completions for both of these.
 
 Note that you need the exact theme name within the brackets, they are as follows:
 - `Snazzy Plus`
 - `Snazzy Plus w/ Italics`
 - `Snazzy Plus - Darker`
 - `Snazzy Plus - Darker w/ Italics`

## Changes

1.3.0 - Added variants with italic keywords for those who use Operator/Dank Mono

1.2.3 - Adjusted colors of Activity bar

1.2.2 - readme adjustments

1.2.0 - Added a darker version for those who prefer higher contrast!

1.1.0 - Initial release

## Credits

- [vscode-snazzy-operator](https://github.com/aaronthomas/vscode-snazzy-operator)
- [vscode-snazzy](https://github.com/alexanderbast/vscode-snazzy)
- [hyper-snazzy](https://github.com/sindresorhus/hyper-snazzy)
