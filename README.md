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

**My prefered extensions:**
```
code --install-extension eamodio.gitlens
code --install-extension Fudge.auto-using
code --install-extension jchannon.csharpextensions
code --install-extension ms-mssql.mssql
code --install-extension ms-vscode.csharp
code --install-extension ms-vscode.vs-keybindings
code --install-extension msjsdiag.debugger-for-chrome
code --install-extension PeterJausovec.vscode-docker
code --install-extension vscode-icons-team.vscode-icons
```
