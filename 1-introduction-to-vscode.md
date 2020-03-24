<a id="building-applications"></a>

## 1、vscode相关

```js
// 将设置放入此文件中以覆盖默认设置
{
    "typescript.check.tscVersion": false,
    "window.zoomLevel": 0,
    "files.autoSave": "off",
    "typescript.updateImportsOnFileMove.enabled": "always",
    "git.confirmSync": false,
    "editor.minimap.enabled": true,
    "workbench.startupEditor": "newUntitledFile",
    "git.autofetch": true,
    "eslint.validate": [
        "javascript",
        "javascriptreact",
        "vue"
    ],
    "[html]": {
        "editor.defaultFormatter": "HookyQR.beautify"
    },
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[json]": {
        "editor.defaultFormatter": "HookyQR.beautify"
    },
    "vetur.validation.template": true,
    "vetur.format.enable": true,
    "vetur.format.defaultFormatter.html": "prettier",
    "vetur.format.defaultFormatter.js": "prettier",
    "vetur.format.defaultFormatter.less": "prettier",
    "vetur.format.defaultFormatterOptions": {
        "prettier": {
            "printWidth": 200,
            "singleQuote": true, // 使用单引号
            "semi": true, // 末尾使用分号
            "tabWidth": 4,
            "arrowParens": "avoid",
            "bracketSpacing": true,
            "proseWrap": "preserve" // 代码超出是否要换行 preserve保留
        }
    },
    "prettier.singleQuote": true,
    "prettier.semi": false,
    "javascript.format.insertSpaceBeforeFunctionParenthesis": true,
    "workbench.settings.editor": "json",
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "[vue]": {
        "editor.defaultFormatter": "octref.vetur"
    },
    "git.enableSmartCommit": true
}
```