# terminal

```
{
    "$help": "https://aka.ms/terminal-documentation",
    "$schema": "https://aka.ms/terminal-profiles-schema",
    "actions": [
        {
            "command": {
                "action": "splitPane",
                "split": "auto",
                "splitMode": "duplicate",
                "profile": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}"
            },
            "keys": "ctrl+shift+d"
        },
        {
            "command": "newTab",
            "keys": "ctrl+shift+t"
        }
    ],
    "alwaysOnTop": true,
    "alwaysShowNotificationIcon": true,
    "centerOnLaunch": false,
    "confirmCloseAllTabs": true,
    "copyOnSelect": true,
    "defaultProfile": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
    "firstWindowPreference": "persistedWindowLayout",
    "focusFollowMouse": true,
    "initialCols": 120,
    "initialRows": 30,
    "launchMode": "default",
    "minimizeToNotificationArea": true,
    "newTabMenu": [
        {
            "type": "remainingProfiles"
        }
    ],
    "profiles": {
        "defaults": {
            "antialiasingMode": "cleartype",
            "backgroundImageOpacity": 1,
            "closeOnExit": "always",
            "colorScheme": "One Half Dark",
            "elevate": true,
            "font": {
                "face": "Cascadia Code",
                "features": {
                    "calt": 1,
                    "ss01": 1
                },
                "size": 14
            },
            "historySize": 5000,
            "opacity": 100,
            "padding": "8",
            "scrollbarState": "visible",
            "useAcrylic": false
        },
        "list": [
            {
                "guid": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
                "hidden": false,
                "name": "Windows PowerShell"
            },
            {
                "colorScheme": "AI Theme",
                "commandline": "powershell.exe -NoExit -Command \"& {Get-ChildItem -Directory; Write-Host 'AI Development Environment Ready' -ForegroundColor Cyan}\"",
                "cursorShape": "filledBox",
                "font": {
                    "face": "Cascadia Code",
                    "size": 16,
                    "weight": "medium"
                },
                "guid": "{16d6a449-8945-4960-b923-cd6cd5e88d09}",
                "icon": "%ICON_PATH%\\white.png",
                "name": "Neb.ai",
                "startingDirectory": "%USERPROFILE%\\AI-Projects"
            },
            {
                "colorScheme": "Python Theme",
                "commandline": "cmd.exe /k \"%PYTHON_VENV_PATH%\\Scripts\\activate && python -V && echo Python Environment Ready\"",
                "cursorShape": "filledBox",
                "guid": "{2b189f96-78c5-4932-b532-8e5d0a8469d7}",
                "icon": "\ud83d\udc0d",
                "name": "Python Dev",
                "startingDirectory": "%USERPROFILE%\\Python-Projects"
            },
            {
                "colorScheme": "Node Theme",
                "commandline": "powershell.exe -NoExit -Command \"& {node -v; npm -v; Write-Host 'Node.js Environment Ready' -ForegroundColor Yellow; npm start}\"",
                "cursorShape": "filledBox",
                "guid": "{3c89f96a-78c5-4932-b532-8e5d0a8469d8}",
                "icon": "none",
                "name": "Node.js Dev",
                "startingDirectory": "%USERPROFILE%\\Node-Projects"
            },
            {
                "backgroundImage": "ms-appdata:///roaming/ollama-terminal-bg.png",
                "colorScheme": "Ollama Theme",
                "commandline": "powershell.exe -NoExit -Command \"& {Write-Host 'Ollama Terminal - Ready for commands' -ForegroundColor Green}\"",
                "cursorShape": "filledBox",
                "font": {
                    "face": "Cascadia Code",
                    "size": 16,
                    "weight": "medium"
                },
                "guid": "{4d6a449b-8945-4960-b923-cd6cd5e88d09}",
                "icon": "\ud83e\udd16",
                "name": "Ollama",
                "opacity": 85,
                "startingDirectory": "%USERPROFILE%\\AI-Projects"
            },
            {
                "guid": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
                "hidden": false,
                "name": "bash",
                "source": "Windows.Terminal.Wsl",
                "colorScheme": "Ollama Theme",
                "startingDirectory": "%USERPROFILE%",
                "commandline": "wsl.exe -d Ubuntu -e bash -c 'bash --version && echo Bash Ready'"
            },
            {
                "guid": "{eda29729-b581-4ae5-986c-3d58f8d632d8}",
                "hidden": false,
                "name": "Profile 14"
            },
            {
                "guid": "{c7f3034e-d79a-428b-870d-f396b67f91c3}",
                "name": "AI Models",
                "colorScheme": "AI Theme",
                "commandline": "powershell.exe -NoExit -Command \"& {%AI_VENV%\\Scripts\\activate; Write-Host 'AI Models - Virtual env activated' -ForegroundColor Green}\"",
                "cursorShape": "filledBox",
                "icon": "%ICON_PATH%\\ai-icon.png",
                "startingDirectory": "%USERPROFILE%\\AI-Projects"
            },
            {
                "guid": "{some-guid}",
                "hidden": false,
                "name": "AI - Neb.ai",
                "commandline": "powershell.exe -NoExit -Command \"& {%AI_VENV%\\Scripts\\activate; python -V; Write-Host 'Python Environment Ready' -ForegroundColor Green}\"",
                "icon": "%ICON_PATH%\\nebai.png"
            },
            {
                "guid": "{some-other-guid}",
                "hidden": false,
                "name": "AI - Ollama",
                "commandline": "powershell.exe -NoExit -Command \"& {%AI_VENV%\\Scripts\\activate; python -V; Write-Host 'Python Environment Ready' -ForegroundColor Green}\"",
                "icon": "%ICON_PATH%\\ollama.png"
            }
        ]
    },
    "schemes": [
        {
            "background": "#1E1E1E",
            "black": "#1E1E1E",
            "blue": "#569CD6",
            "brightBlack": "#808080",
            "brightBlue": "#9CDCFE",
            "brightCyan": "#4EC9B0",
            "brightGreen": "#608B4E",
            "brightPurple": "#C586C0",
            "brightRed": "#D16969",
            "brightWhite": "#D4D4D4",
            "brightYellow": "#DCDCAA",
            "cursorColor": "#FFFFFF",
            "cyan": "#4EC9B0",
            "foreground": "#D4D4D4",
            "green": "#608B4E",
            "name": "AI Theme",
            "purple": "#C586C0",
            "red": "#D16969",
            "selectionBackground": "#264F78",
            "white": "#D4D4D4",
            "yellow": "#DCDCAA"
        },
        {
            "background": "#002B36",
            "black": "#073642",
            "blue": "#268BD2",
            "brightBlack": "#002B36",
            "brightBlue": "#839496",
            "brightCyan": "#93A1A1",
            "brightGreen": "#586E75",
            "brightPurple": "#6C71C4",
            "brightRed": "#CB4B16",
            "brightWhite": "#FDF6E3",
            "brightYellow": "#657B83",
            "cursorColor": "#839496",
            "cyan": "#2AA198",
            "foreground": "#839496",
            "green": "#859900",
            "name": "Node Theme",
            "purple": "#D33682",
            "red": "#DC322F",
            "selectionBackground": "#073642",
            "white": "#EEE8D5",
            "yellow": "#B58900"
        },
        {
            "background": "#0C0C0C",
            "black": "#0C0C0C",
            "blue": "#0037DA",
            "brightBlack": "#767676",
            "brightBlue": "#3B78FF",
            "brightCyan": "#61D6D6",
            "brightGreen": "#16C60C",
            "brightPurple": "#B4009E",
            "brightRed": "#E74856",
            "brightWhite": "#F2F2F2",
            "brightYellow": "#F9F1A5",
            "cursorColor": "#FFFFFF",
            "cyan": "#3A96DD",
            "foreground": "#CCCCCC",
            "green": "#13A10E",
            "name": "Ollama Theme",
            "purple": "#881798",
            "red": "#C50F1F",
            "selectionBackground": "#FFFFFF",
            "white": "#CCCCCC",
            "yellow": "#C19C00"
        },
        {
            "background": "#282C34",
            "black": "#282C34",
            "blue": "#61AFEF",
            "brightBlack": "#5C6370",
            "brightBlue": "#61AFEF",
            "brightCyan": "#56B6C2",
            "brightGreen": "#98C379",
            "brightPurple": "#C678DD",
            "brightRed": "#E06C75",
            "brightWhite": "#FFFFFF",
            "brightYellow": "#E5C07B",
            "cursorColor": "#FFFFFF",
            "cyan": "#56B6C2",
            "foreground": "#ABB2BF",
            "green": "#98C379",
            "name": "Python Theme",
            "purple": "#C678DD",
            "red": "#E06C75",
            "selectionBackground": "#3E4451",
            "white": "#ABB2BF",
            "yellow": "#E5C07B"
        }
    ],
    "showTerminalTitleInTitlebar": true,
    "snapToGridOnResize": true,
    "tabSwitcherMode": "mru",
    "tabWidthMode": "titleLength",
    "theme": "legacySystem",
    "themes": [],
    "trimBlockSelection": true,
    "trimPaste": true,
    "useAcrylicInTabRow": false,
    "windowingBehavior": "useExisting",
    "keybindings": [
        {
            "command": "closeTab",
            "keys": "ctrl+w"
        },
        {
            "command": "nextTab",
            "keys": "ctrl+tab"
        },
        {
            "command": "prevTab",
            "keys": "ctrl+shift+tab"
        },
        {
            "command": "duplicateTab",
            "keys": "ctrl+shift+u"
        },
        {
            "command": "openSettings",
            "keys": "ctrl+,"
        },
        {
            "command": "zoomIn",
            "keys": "ctrl++"
        },
        {
            "command": "zoomOut",
            "keys": "ctrl+-"
        },
        {
            "command": {
                "action": "duplicatePane",
                "split": "auto"
            },
            "keys": "ctrl+shift+u"
        }
    ]
}

{
	"persistedWindowLayouts" : 
	[
		{
			"initialPosition" : "262,55",
			"initialSize" : 
			{
				"height" : 676,
				"width" : 912
			},
			"launchMode" : "default",
			"tabLayout" : 
			[
				{
					"action" : "newTab",
					"commandline" : "%SystemRoot%\\System32\\WindowsPowerShell\\v1.0\\powershell.exe",
					"profile" : "Windows PowerShell",
					"sessionId" : "{954f136e-6aae-49d6-ad7d-c0eccd1d56bc}",
					"startingDirectory" : "C:\\Users\\johnw\\OneDrive\\Desktop",
					"suppressApplicationTitle" : false,
					"tabTitle" : "Windows PowerShell"
				},
				{
					"action" : "newTab",
					"commandline" : "%SystemRoot%\\System32\\WindowsPowerShell\\v1.0\\powershell.exe",
					"profile" : "Windows PowerShell",
					"sessionId" : "{cec59d9c-0c6b-4621-999f-0c68fffadb9b}",
					"startingDirectory" : "C:\\Users\\johnw",
					"suppressApplicationTitle" : false,
					"tabTitle" : "Windows PowerShell"
				}
			]
		}
	]
}
```
