# ตั้งค่า VS Code สำหรับฉัน
> ต้องไม่ลืมติดตั้งฟอนต์ [Fira Mono](https://fonts.google.com/specimen/Fira+Mono) 
```sh
{
    "editor.cursorStyle": "line-thin",
    "window.zoomLevel": 0,
    "editor.tabSize": 4,
    "editor.detectIndentation": false,
    // "editor.renderWhitespace": "all",
    // "editor.lineHeight": 28,
    "editor.formatOnSave": true,
    "html.format.wrapLineLength": 0,
    "html.suggest.angular1": false,
    "html.suggest.ionic": false,
    "editor.letterSpacing": 0,
    "editor.fontLigatures": true,
    "explorer.openEditors.visible": 0,
    "phpfmt.psr2": true,
    "phpfmt.indent_with_space": 4,
    "vscode-php-cs-fixer.fixOnSave": false,
    "vscode-php-cs-fixer.rules": "@PSR1,@PSR2,@Symfony,-yoda_style",
    // Enable per-language
    "[php]": {
        "editor.formatOnSave": false,
        "editor.tabSize": 4,
        "editor.defaultFormatter": "kokororin.vscode-phpfmt"
    },
    "phpfmt.passes": [
        // "AllmanStyleBraces",
        "LongArray",
        // "SpaceAroundParentheses",
        "AlignGroupDoubleArrow",
        "ConvertOpenTagWithEcho",
        "IndentTernaryConditions",
        "MergeElseIf",
        "NewLineBeforeReturn",
        "RemoveSemicolonAfterCurly",
        "ReplaceBooleanAndOr",
        "SmartLnAfterCurlyOpen",
    ],
    "explorer.confirmDragAndDrop": false,
    "window.title": "${activeEditorMedium}${separator}${rootName} ${dirty}",
    "editor.wordSeparators": "`~!@%^&*()=+-[{]}\\|;:'\",.<>/?",
    "workbench.startupEditor": "newUntitledFile",
    // "git.autoRepositoryDetection": false,
    // "git.autorefresh": false,
    // "git.detectSubmodules": false,
    "files.autoSave": "off",
    // "editor.minimap.enabled": false,
    "editor.fontSize": 15,
    "breadcrumbs.enabled": false,
    "workbench.colorTheme": "Twilight",
    "workbench.iconTheme": "vscode-icons"
}
```

# Extensions สำหรับฉัน
- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) (Jun Han)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) (Jun Han)
- [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify) (HookyQR)
- [ci-snippets](https://marketplace.visualstudio.com/items?itemName=secato.ci-snippets) (secato)
- [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion) (Zignd)
- [jQuery Code Snippets](https://marketplace.visualstudio.com/items?itemName=donjayamanne.jquerysnippets) (Don Jayamanne)
- [Path Autocomplete](https://marketplace.visualstudio.com/items?itemName=ionutvmi.path-autocomplete) (Mihai Vilcu)
- [PHP intellisense for codeigniter](https://marketplace.visualstudio.com/items?itemName=small.php-ci) (small)
- [phpfmt - PHP formatter](https://marketplace.visualstudio.com/items?itemName=kokororin.vscode-phpfmt) (kokororin)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) (Esben Petersen)
- [Twilight Theme](https://marketplace.visualstudio.com/items?itemName=gerane.Theme-Twilight) (gerane)
- [vscode-icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons) (Roberto Huertas)
- [Angular Essentials](https://marketplace.visualstudio.com/items?itemName=johnpapa.angular-essentials) (John Papa)
- [Angular 6 Snippets - TypeScript, Html, Angular Material, ngRx, RxJS & Flex Layout](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode) (Mikael Morlund)
