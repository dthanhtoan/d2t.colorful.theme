<h2 align="center">
	<img src="https://raw.githubusercontent.com/dthanhtoan/d2t.colorful.theme/main/images/logo.png" width="100" alt="Logo"/><br/><br/>
	D2T Colorful Theme for <a href="https://marketplace.visualstudio.com/items?itemName=dthanhtoan.d2t-colorful-theme">Visual Studio Code</a>
</h2>

<br/>

![image-1](https://raw.githubusercontent.com/dthanhtoan/d2t.colorful.theme/main/images/jsx.png)

<br/>

![image-2](https://raw.githubusercontent.com/dthanhtoan/d2t.colorful.theme/main/images/html.png)

## Recomment Setting

### I. Setting

```
{
  "workbench.editor.wrapTabs": true,
  "editor.stickyScroll.enabled": true,
  "editor.cursorSmoothCaretAnimation": true,
  "editor.fontSize": 16,
  "editor.lineHeight": 35,
  "editor.letterSpacing": 0.5,
}
```

### II. Font

<h3>Overpass Mono</h3>

[Download font Overpass Mono](https://fonts.google.com/specimen/Overpass+Mono?query=overpass+mono)

<h3>JetBrains Mono</h3>

[Download font JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono?query=JetBrains+Mono)

### III. Custom CSS

1. Install this theme
2. Install [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) VS Code extension
3. Link the CSS file from this extension in your VS Code settings.json:

   ```
   On Mac:
   {
   "vscode_custom_css.imports": [
       file:///Users/{your username}/.vscode/extensions/dthanhtoan.d2t-colorful-theme-0.4.0/customColor.css"
   ]
   }
   ```

   ```
   On Windows:
   {
   "vscode_custom_css.imports": [
       "file:///C:/Users/{your username}/.vscode/extensions/dthanhtoan.d2t-colorful-theme-0.4.0/customColor.css"
   ]
   }
   ```

   ```
   On Linux:
   {
   "vscode_custom_css.imports": [
       "file:///home/{your username}/.vscode/extensions/dthanhtoan.d2t-colorful-theme-0.4.0/customColor.css"
   ]
   }
   ```

4. From the command panel, select `Reload Custom CSS and JS`. You'll need to run this command every time vscode updates.
