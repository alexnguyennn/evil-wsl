# Evil-WSL-Mode
Evil mode for Emacs overloads for yank/paste from Windows Clipboard for use with wsl.

[Evil-ReplaceWithRegister](https://github.com/Dewdrops/evil-ReplaceWithRegister) was used as the basis for `evil-replace-with-register-wsl`.

## Why?
Running emacs in WSL without an X Server e.g. (VcXsrv/Xming) means you won't be able to access clipboard from windows programs. 

`evil-wsl-mode` mode provides helpers to access `clip.exe` and `Get-ClipboardText` via WSL Interop and fix this problem.
## Dependencies
- PowerShell Core
- Evil mode

## TODO
- Fix count on paste function - can't make it make count optional yet
