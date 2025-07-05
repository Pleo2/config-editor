## Editor Code Config

```json
{
        "workbench.colorTheme": "Codely Dark Theme",
        "workbench.iconTheme": "material-icon-theme",
        "window.zoomLevel": 1,
        "window.titleBarStyle": "custom",
        "window.customTitleBarVisibility": "never",
        "workbench.activityBar.location": "hidden",
        "workbench.sideBar.location": "right",
        "workbench.editor.showTabs": "multiple",
        "breadcrumbs.enabled": false,
        "workbench.panel.showLabels": false,
        "workbench.tips.enabled": false,
        "editor.fontFamily": "Cascadia code",
        "editor.fontSize": 12,
        "editor.fontWeight": "bold",
        "editor.lineHeight": 1.8,
        "editor.fontLigatures": true,
        "custom-ui-style.font.sansSerif": "Cascadia Code",
        "terminal.integrated.fontFamily": "Cascadia Code",
        "terminal.integrated.fontSize": 12,
        "editor.tokenColorCustomizations": {
                "textMateRules": [
                        {
                                "scope": "comment",
                                "settings": {
                                        "fontStyle": "italic"
                                }
                        }
                ]
        },
        "workbench.colorCustomizations": {
                "editorCursor.background": "#000000",
                "editorOverviewRuler.wordHighlightStrongForeground": "#0000",
                "editorOverviewRuler.selectionHighlightForeground": "#0000",
                "editorOverviewRuler.rangeHighlightForeground": "#0000",
                "editorOverviewRuler.wordHighlightForeground": "#0000",
                "editorOverviewRuler.bracketMatchForeground": "#0000",
                "editorOverviewRuler.findMatchForeground": "#0000",
                "editorOverviewRuler.modifiedForeground": "#0000",
                "editorOverviewRuler.deletedForeground": "#0000",
                "editorOverviewRuler.warningForeground": "#0000",
                "editorOverviewRuler.addedForeground": "#0000",
                "editorOverviewRuler.errorForeground": "#0000",
                "editorOverviewRuler.infoForeground": "#0000",
                "editorOverviewRuler.border": "#0000",
                "[Aura Dracula Spirit (Soft)]": {
                        "editorSuggestWidget.selectedBackground": "#3A334B",
                        "sideBar.background": "#191521"
                }
        },
        "custom-ui-style.electron": {
                "titleBarStyle": "hiddenInset",
                "trafficLightPosition": {
                        "x": 20,
                        "y": 16
                }
        },
        "custom-ui-style.stylesheet": {
                ".notification-toast": "box-shadow: none !important",
                ".quick-input-widget.show-file-icons": "box-shadow: none !important",
                ".quick-input-widget": "top: 25vh !important",
                ".quick-input-list .scrollbar": "display: none",
                ".monaco-action-bar.quick-input-inline-action-bar": "display: none",
                ".editor-widget.find-widget": "box-shadow: none; border-radius: 4px",
                ".quick-input-titlebar": "background: #100B15 !important",
                ".monaco-workbench .part.editor > .content .editor-group-container > .title.title-border-bottom:after": "display: none",
                ".monaco-scrollable-element > .shadow.top": "display: none",
                ".sidebar .title-label": "padding: 0 !important",
                ".sidebar": "border: none !important",
                ".monaco-workbench .monaco-list:not(.element-focused):focus:before": "outline: none !important",
                ".monaco-list-row.focused": "outline: none !important",
                ".monaco-editor .scroll-decoration": "display: none",
                ".title-actions": "display: none !important",
                ".title.show-file-icons .label-container .monaco-icon-label.file-icon": "justify-content: center; padding: 0 !important",
                ".title .monaco-icon-label:after": "margin-right: 0",
                ".monaco-workbench .part.editor > .content .editor-group-container > .title > .label-container > .title-label": "padding-left: 60px",
                ".title .monaco-icon-label.file-icon": "margin: 0 60px"
        },
        "editor.multiCursorModifier": "ctrlCmd",
        "editor.cursorBlinking": "solid",
        "editor.cursorStyle": "line",
        "editor.stickyScroll.enabled": false,
        "editor.minimap.enabled": false,
        "editor.lineNumbers": "relative",
        "editor.tabSize": 8,
        "editor.detectIndentation": false,
        "editor.wordWrap": "on",
        "editor.wordWrapColumn": 120,
        "editor.wrappingStrategy": "advanced",
        "editor.rulers": [
                120
        ],
        "editor.mouseWheelZoom": true,
        "editor.mouseWheelScrollSensitivity": 2,
        "workbench.list.mouseWheelScrollSensitivity": 2,
        "editor.accessibilitySupport": "off",
        "editor.renderLineHighlight": "none",
        "editor.renderWhitespace": "none",
        "editor.guides.indentation": false,
        "editor.showFoldingControls": "never",
        "editor.matchBrackets": "never",
        "editor.occurrencesHighlight": "off",
        "editor.selectionHighlight": false,
        "editor.colorDecorators": false,
        "scm.diffDecorations": "none",
        "git.decorations.enabled": false,
        "editor.scrollbar.horizontal": "hidden",
        "editor.scrollbar.vertical": "hidden",
        "editor.overviewRulerBorder": false,
        "editor.hideCursorInOverviewRuler": true,
        "editor.quickSuggestions": {
                "other": true
        },
        "editor.suggestOnTriggerCharacters": true,
        "editor.tabCompletion": "on",
        "editor.snippetSuggestions": "top",
        "emmet.triggerExpansionOnTab": true,
        "editor.parameterHints.enabled": false,
        "editor.hover.enabled": true,
        "editor.lightbulb.enabled": "off",
        "editor.links": false,
        "editor.codeLens": false,
        "editor.formatOnSave": true,
        "files.autoSave": "afterDelay",
        "files.trimTrailingWhitespace": true,
        "files.insertFinalNewline": true,
        "explorer.compactFolders": false,
        "explorer.confirmDragAndDrop": false,
        "explorer.confirmDelete": false,
        "explorer.confirmPasteNative": false,
        "explorer.decorations.badges": false,
        "workbench.tree.enableStickyScroll": false,
        "workbench.tree.renderIndentGuides": "none",
        "workbench.tree.indent": 24,
        "files.exclude": {
                "**/.git": true,
                "**/.svn": true,
                "**/.hg": true,
                "**/CVS": true,
                "**/.DS_Store": true,
                "**/Thumbs.db": true,
                "**/node_modules": true,
                "**/bower_components": true
        },
        "search.exclude": {
                "**/node_modules": true,
                "**/bower_components": true,
                "**/*.code-search": true
        },
        "git.autofetch": true,
        "git.enableSmartCommit": true,
        "git.confirmSync": false,
        "terminal.integrated.tabs.enabled": true,
        "terminal.integrated.tabs.showActions": "always",
        "terminal.integrated.tabs.showActiveTerminal": "always",
        "terminal.integrated.tabs.location": "left",
        "javascript.updateImportsOnFileMove.enabled": "always",
        "typescript.updateImportsOnFileMove.enabled": "always",
        "php.validate.executablePath": "C:\\Users\\jo.moreno\\.config\\herd\\bin\\php83\\php.exe",
        "dart.flutterSdkPath": "C:\\Users\\jo.moreno\\Documents\\flutter",
        "dart.debugExternalPackageLibraries": false,
        "dart.debugSdkLibraries": false,
        "[jsonc]": {
                "editor.defaultFormatter": "vscode.json-language-features"
        },
        "[typescriptreact]": {
                "editor.defaultFormatter": "esbenp.prettier-vscode"
        },
        "[vue]": {
                "editor.defaultFormatter": "Vue.volar"
        },
        "prettier": {
                "enable": true,
                "semi": true,
                "tabWidth": 8,
                "singleQuote": true
        },
        "reactSnippets.settings.importReactOnTop": false,
        "colorize.languages": [
                "javascript",
                "typescriptreact",
                "css",
                "html"
        ],
        "update.mode": "none",
        "extensions.ignoreRecommendations": true,
        "windsurf.marketplaceGalleryItemURL": "https://marketplace.visualstudio.com/items",
        "windsurf.marketplaceExtensionGalleryServiceURL": "https://marketplace.visualstudio.com/_apis/public/gallery",
        "workbench.statusBar.visible": false
}

```
