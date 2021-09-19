# Visual Studio Code

> https://code.visualstudio.com/
>
> https://code.visualstudio.com/insiders/


## Extensions By Language

https://marketplace.visualstudio.com/search?term=%40itmcdev&target=VSCode&category=All%20categories&sortBy=Relevance

## Generic Config

```json
{
  "atomKeymap.promptV3Features": true,
  // Controls the font family.
  "editor.fontFamily": "Source Code Pro, Consolas, 'Courier New', monospace",
  // Columns at which to show vertical rulers
  "editor.rulers": [80, 120],
  "editor.wordWrap": true,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.formatOnPaste": false,
  "gitlens.advanced.messages": {
    "suppressCommitHasNoPreviousCommitWarning": false,
    "suppressCommitNotFoundWarning": false,
    "suppressFileNotUnderSourceControlWarning": false,
    "suppressGitVersionWarning": false,
    "suppressLineUncommittedWarning": false,
    "suppressNoRepositoryWarning": false
  },
  "javascript.updateImportsOnFileMove.enabled": "always",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorCustomizations": {
    "activityBarBadge.background": "#7CB342",
    "list.activeSelectionForeground": "#7CB342",
    "list.inactiveSelectionForeground": "#7CB342",
    "list.highlightForeground": "#7CB342",
    "scrollbarSlider.activeBackground": "#7CB34250",
    "editorSuggestWidget.highlightForeground": "#7CB342",
    "textLink.foreground": "#7CB342"
  },
  "explorer.confirmDragAndDrop": false,
  "window.menuBarVisibility": "classic",
  "workbench.editor.enablePreview": false,
  "workbench.editor.enablePreviewFromQuickOpen": false,
  "explorer.confirmDelete": false,
  "workbench.sideBar.location": "left",
  "python.linting.flake8Enabled": true,
  "editor.formatOnSave": true,
  "editor.fontLigatures": true,
  "files.eol": "\n",
  "typescript.updateImportsOnFileMove.enabled": "always",
  "editor.suggestSelection": "first",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "editor.lineHeight": 14,
  "editor.find.addExtraSpaceOnTop": false,
  "debug.console.fontSize": 13,
  "terminal.integrated.fontSize": 13,
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "files.associations": {
    "*.twig": "twig"
  },
  "workbench.editorAssociations": {
    "*.ipynb": "jupyter.notebook.ipynb"
  },
  "tabnine.experimentalAutoImports": true,
  "window.zoomLevel": 1
}
```