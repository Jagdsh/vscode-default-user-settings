# vscode-default-settings
VS Code Default settings

```
{
    "editor.renderWhitespace": "all",
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "java.configuration.checkProjectSettingsExclusions": false,
    "diffEditor.ignoreTrimWhitespace": false,
    "terraform.indexing": {
        "enabled": false,
        "liveIndexing": false,
        "delay": 500,
        "exclude": [
            ".terraform/**/*",
            "**/.terraform/**/*"
        ]
    },
    "files.autoSave": "afterDelay",
    "[javascript]": {
        "editor.defaultFormatter": "vscode.typescript-language-features"
    },
    "java.semanticHighlighting.enabled": true,
    "java.requirements.JDK11Warning": false,
    "[json]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "workbench.colorTheme": "Tomorrow Night Bright",
    "terminal.integrated.automationShell.osx": "/bin/zsh",
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.accessibilitySupport": "off",
    "git.confirmSync": false,
    "explorer.confirmDragAndDrop": false,
    "mssql.connections": [
        {
            "server": "{{put-server-name-here}}",
            "database": "{{put-database-name-here}}",
            "user": "{{put-username-here}}",
            "password": ""
        }
    ],
    "vsnotes.defaultNotePath": "/home/kali/Documents/oswe/oswe-prep",
    "workbench.editorAssociations": {
        "*.ipynb": "jupyter.notebook.ipynb"
    },
    "highlight.regexes": {
        "((?:<!-- *)?(?:#|// @|//|./\\*+|<!--|--|\\* @|{!|{{!--|{{!) *TODO(?:\\s*\\([^)]+\\))?:?)((?!\\w)(?: *-->| *\\*/| *!}| *--}}| *}}|(?= *(?:[^:]//|/\\*+|<!--|@|--|{!|{{!--|{{!))|(?: +[^\\n@]*?)(?= *(?:[^:]//|/\\*+|<!--|@|--(?!>)|{!|{{!--|{{!))|(?: +[^@\\n]+)?))": {
            "filterFileRegex": ".*(?<!CHANGELOG.md)$",
            "decorations": [{
                    "overviewRulerColor": "#ffcc00",
                    "backgroundColor": "#ffcc00",
                    "color": "#1f1f1f",
                    "fontWeight": "bold"
                },
                {
                    "backgroundColor": "#ffcc00",
                    "color": "#1f1f1f"
                }
            ]
        },
        "((?:<!-- *)?(?:#|// @|//|./\\*+|<!--|--|\\* @|{!|{{!--|{{!) *(?:FIXME|FIX|BUG|UGLY|DEBUG|HACK)(?:\\s*\\([^)]+\\))?:?)((?!\\w)(?: *-->| *\\*/| *!}| *--}}| *}}|(?= *(?:[^:]//|/\\*+|<!--|@|--|{!|{{!--|{{!))|(?: +[^\\n@]*?)(?= *(?:[^:]//|/\\*+|<!--|@|--(?!>)|{!|{{!--|{{!))|(?: +[^@\\n]+)?))": {
            "filterFileRegex": ".*(?<!CHANGELOG.md)$",
            "decorations": [{
                    "overviewRulerColor": "#cc0000",
                    "backgroundColor": "#cc0000",
                    "color": "#1f1f1f",
                    "fontWeight": "bold"
                },
                {
                    "backgroundColor": "#cc0000",
                    "color": "#1f1f1f"
                }
            ]
        },
        "((?:<!-- *)?(?:#|// @|//|./\\*+|<!--|--|\\* @|{!|{{!--|{{!) *(?:REVIEW|OPTIMIZE|TSC)(?:\\s*\\([^)]+\\))?:?)((?!\\w)(?: *-->| *\\*/| *!}| *--}}| *}}|(?= *(?:[^:]//|/\\*+|<!--|@|--|{!|{{!--|{{!))|(?: +[^\\n@]*?)(?= *(?:[^:]//|/\\*+|<!--|@|--(?!>)|{!|{{!--|{{!))|(?: +[^@\\n]+)?))": {
            "filterFileRegex": ".*(?<!CHANGELOG.md)$",
            "decorations": [{
                    "overviewRulerColor": "#00ccff",
                    "backgroundColor": "#00ccff",
                    "color": "#1f1f1f",
                    "fontWeight": "bold"
                },
                {
                    "backgroundColor": "#00ccff",
                    "color": "#1f1f1f"
                }
            ]
        },
        "((?:<!-- *)?(?:#|// @|//|./\\*+|<!--|--|\\* @|{!|{{!--|{{!) *(?:IDEA)(?:\\s*\\([^)]+\\))?:?)((?!\\w)(?: *-->| *\\*/| *!}| *--}}| *}}|(?= *(?:[^:]//|/\\*+|<!--|@|--|{!|{{!--|{{!))|(?: +[^\\n@]*?)(?= *(?:[^:]//|/\\*+|<!--|@|--(?!>)|{!|{{!--|{{!))|(?: +[^@\\n]+)?))": {
            "filterFileRegex": ".*(?<!CHANGELOG.md)$",
            "decorations": [{
                    "overviewRulerColor": "#cc00cc",
                    "backgroundColor": "#cc00cc",
                    "color": "#1f1f1f",
                    "fontWeight": "bold"
                },
                {
                    "backgroundColor": "#cc00cc",
                    "color": "#1f1f1f"
                }
            ]
        }
    },
    "docker.showStartPage": false,
    "security.workspace.trust.untrustedFiles": "newWindow",
    "bracket-pair-colorizer-2.depreciation-notice": false,
    "git.autorefresh": false,
    "remote.SSH.configFile": "/home/kali/.ssh/id_rsa-remote-ssh",
    "gitlens.advanced.messages": {
        "suppressGitDisabledWarning": true,
        "suppressGitMissingWarning": true
    },
    "vsnotes.ignorePatterns": [
        "^\\.",
        "*.py",
        "*.java",
        "*.csv"
    ],
    "javascript.updateImportsOnFileMove.enabled": "never",
    "terraform.languageServer.enable": true,
    "window.zoomLevel": 1,
    "js/ts.implicitProjectConfig.experimentalDecorators": true,
    "jest.autoRun": "off",
    "application.shellEnvironmentResolutionTimeout": 20
}
```
