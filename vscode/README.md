Command I used to generate a file of all extensions

```ps1
code --list-extensions | % { "code --install-extension $_" } > install_extensions.ps1
```