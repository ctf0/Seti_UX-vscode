# Seti_UX

a vscode port for [Seti_ST3](https://github.com/ctf0/Seti_ST3) & [Seti_UX](https://github.com/ctf0/Seti_UX)

## Config

- to change the tab dirty colors, add

    ```jsonc
    "workbench.colorCustomizations": {
        // ...
        "[Seti_UX]": {
            "tab.activeModifiedBorder": "#ff4545",
            "tab.inactiveModifiedBorder": "#ff454580",
            "tab.unfocusedActiveModifiedBorder": "#ff454580",
            "tab.unfocusedInactiveModifiedBorder": "#ff454540",
        },
    }
    ```

- also check [Customizing a Color Theme](https://code.visualstudio.com/docs/getstarted/themes#_customizing-a-color-theme) for any extra customizations needed.

### Custom css

- [gist](https://gist.github.com/ctf0/bebe3f0884664ee6e4eb6972f560e5a7)

### Notes

- colors are slightly different from the original, however u can use [this color sheet](https://github.com/ctf0/Seti_UX/blob/master/colors.md) as a guide.
- not all languages are covered, so either create a PR or open a [ticket](https://github.com/ctf0/Seti_UX-vscode/issues) with the `scope & color` needed and i will add them.
- some parts of the UI isn't possible to port without the use of [Custom Css](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css)
- a big draw back for the syntax HL is not having background support, check https://github.com/microsoft/vscode/issues/3429
