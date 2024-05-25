# KRNSH

### I doubt anyone will find this extension useful besides me. Still, here's the install process:

1. Download KRNSH
2. Rename to "krnsh"
3. Add krnsh in "C:\Users\user-x\.vscode\extensions"
2. In VS Code, open settings.json and add following JSON
    "files.associations": {
        "*.txt": "krnsh",
    },
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": "krnsh.comments",
                "settings": {
                    "foreground": "#6A9955",
                }
            },
            {
                "scope": "krnsh.abbreviations",
                "settings": {
                    "foreground": "#4EC9B0",
                }
            },
            {
                "scope": "krnsh.conjunctions",
                "settings": {
                    "foreground": "#4EC9B0",
                }
            },
            {
                "scope": "krnsh.links",
                "settings": {
                    "foreground": "#007bff",
                }
            },
            {
                "scope": "krnsh.comma",
                "settings": {
                    "foreground": "#C586C0",
                }
            },
            {
                "scope": "krnsh.period",
                "settings": {
                    "foreground": "#CE9178",
                }
            },
            {
                "scope": "krnsh.symbols",
                "settings": {
                    "foreground": "#569CD6",
                }
            }
        ]
    },
