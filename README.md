# vscode-settings
My Visual Studio Code Settings

**Show installed extensions:**

UNIX:
```
code --list-extensions | xargs -L 1 echo code --install-extension
```
Windows (PowerShell, e. g. using VSCode's integrated Terminal):
```
code --list-extensions | % { "code --install-extension $_" }
```
