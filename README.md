# VSConfig
settings.json of vs code
{
	"editor.suggestSelection": "first",
	"vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
	"workbench.activityBar.visible": true,
	"workbench.sideBar.location": "right",
	"editor.renderControlCharacters": false,
	"java.semanticHighlighting.enabled": true,
	"files.exclude": {
		"**/.classpath": true,
		"**/.project": true,
		"**/.settings": true,
		"**/.factorypath": true
	},
	"java.home": "C:\\Program Files\\Java\\java-11-openjdk-11.0.7.10-1.windows.redhat.x86_64",
	"java.configuration.checkProjectSettingsExclusions": true,
	"liveServer.settings.donotShowInfoMsg": true,
	"workbench.iconTheme": "material-icon-theme",
	"powermode.enabled": true,
	"workbench.startupEditor": "newUntitledFile",
	"powermode.explosionSize": 7,
	"editor.fontFamily": "Victor Mono",
	"editor.mouseWheelZoom": true,
	"winopacity.opacity": 240,
	//pretier
	"editor.formatOnSave": true,
	"editor.defaultFormatter": "esbenp.prettier-vscode",
	//configuracion de titi de prettier
	"prettier.arrowParens": "avoid",
	"prettier.bracketSpacing": true,
	"prettier.embeddedLanguageFormatting": "auto",
	"prettier.htmlWhitespaceSensitivity": "css",
	"prettier.insertPragma": false,
	"prettier.jsxBracketSameLine": false,
	"prettier.jsxSingleQuote": true,
	"prettier.printWidth": 90,
	"prettier.proseWrap": "preserve",
	"prettier.quoteProps": "as-needed",
	"prettier.requirePragma": false,
	"prettier.semi": false,
	"prettier.singleQuote": true,
	"prettier.useTabs": true,
	"prettier.tabWidth": 2,
	"prettier.trailingComma": "es5",
	"prettier.vueIndentScriptAndStyle": false,

	//colores de los comentarios

	//color alerts
	"workbench.colorCustomizations": {
		//tema que esta mmodificado
		"[Andromeda Italic Bordered]": {
			//notificaciones
			"activityBarBadge.background": "#296399",
			"activityBarBadge.foreground": "#e8eef3",
			"activityBar.activeBorder": "#22F2AE",
			"list.activeSelectionForeground": "#ddd",
			"list.inactiveSelectionForeground": "#ddd",
			"list.highlightForeground": "#6900ff",
			"scrollbarSlider.activeBackground": "#22F2AE",
			"editorSuggestWidget.highlightForeground": "#22F2AE",
			"textLink.foreground": "#22F2AE",
			"progressBar.background": "#22F2AE",
			"tab.activeBorder": "#22F2AE",
			"notificationLink.foreground": "#22F2AE",
			"editorWidget.resizeBorder": "#22F2AE",
			"editorWidget.border": "#22F2AE",
			"settings.modifiedItemIndicator": "#22F2AE",
			"settings.headerForeground": "#22F2AE",
			"panelTitle.activeBorder": "#22F2AE",
			"breadcrumb.activeSelectionForeground": "#22F2AE",
			"menu.selectionForeground": "#22F2AE",
			"menubar.selectionForeground": "#22F2AE",
			"editor.findMatchBorder": "#22F2AE",
			"selection.background": "#22F2AE",
			"statusBarItem.remoteBackground": "#22F2AE",
			"tab.inactiveBackground": "#16171d",
			//parte iferior del visual estudio
			"statusBar.foreground": "#22F2AE",
			"statusBarItem.hoverBackground": "#2E4053",

			//activity bar
			"activityBar.foreground": "#22F2AE",
			"activityBar.activeBackground": "#273746",
			"editor.selectionBackground": "#2896717a",
			"editorLineNumber.activeForeground": "#dac935",
			"editorLineNumber.foreground": "#22F2AE",

			//editor cursor
			"editorCursor.foreground": "#ff5733"
		},
		/* 
    --------------------------
    segundo tema aplicado mi config
    --------------------------
    */
		"[Horizon Italic]": {
			//notificaciones
			"activityBarBadge.background": "#296399",
			"activityBarBadge.foreground": "#e8eef3",
			"activityBar.activeBorder": "#22F2AE",
			"list.activeSelectionForeground": "#ddd",
			"list.inactiveSelectionForeground": "#ddd",
			"list.highlightForeground": "#6900ff",
			"scrollbarSlider.activeBackground": "#22F2AE",
			"editorSuggestWidget.highlightForeground": "#22F2AE",
			"textLink.foreground": "#22F2AE",
			"progressBar.background": "#22F2AE",
			"tab.activeBorder": "#22F2AE",
			"notificationLink.foreground": "#22F2AE",
			"editorWidget.resizeBorder": "#22F2AE",
			"editorWidget.border": "#22F2AE",
			"settings.modifiedItemIndicator": "#22F2AE",
			"settings.headerForeground": "#22F2AE",
			"panelTitle.activeBorder": "#22F2AE",
			"breadcrumb.activeSelectionForeground": "#22F2AE",
			"menu.selectionForeground": "#22F2AE",
			"menubar.selectionForeground": "#22F2AE",
			"editor.findMatchBorder": "#22F2AE",
			"selection.background": "#22F2AE",
			"statusBarItem.remoteBackground": "#22F2AE",
			"tab.inactiveBackground": "#16171d",
			//parte iferior del visual estudio
			"statusBar.foreground": "#22F2AE",
			"statusBarItem.hoverBackground": "#2E4053",

			//activity bar
			"activityBar.foreground": "#22F2AE",
			"activityBar.activeBackground": "#273746",
			"editor.selectionBackground": "#2896717a",
			"editorLineNumber.activeForeground": "#dac935",
			"editorLineNumber.foreground": "#22F2AE",

			//editor cursor
			"editorCursor.foreground": "#ff5733"
		}
	},
	"editor.tokenColorCustomizations": {
		//"comments": "#4ee4ff",

		"textMateRules": [
			{
				"scope": ["comment"],
				"settings": {
					"foreground": "#888",
					"fontStyle": " bold"
				}
			}
		]
	},

	/* 
    -------------------------
    fuente de configuracion
    ------------------------
    */
	"workbench.editor.enablePreview": false,
	"editor.fontLigatures": true,
	"workbench.colorTheme": "Horizon Italic",

	/* braket pair */
	"bracket-pair-colorizer-2.activeScopeCSS": [
		"borderStyle : solid",
		"borderWidth : 1px",
		"borderColor : {color}",
		"opacity: 0.5"
	],
	"editor.cursorBlinking": "expand",
	"terminal.integrated.cursorStyle": "line",
	"terminal.integrated.cursorWidth": 2,
	"editor.cursorWidth": 2,
	"editor.cursorSmoothCaretAnimation": true
}
