# Export
Export with
```bash
echo "echo \"$(cursor --list-extensions | tr '\n' ' ')\" | xargs -n 1 cursor --install-extension"
```

This outputs the extensions as an import bash command (the one below)

# Import
```bash
echo "alefragnani.project-manager anthropic.claude-code anysphere.cursorpyright ardonplay.vscode-jetbrains-icon-theme bmewburn.vscode-intelephense-client devsense.composer-php-vscode devsense.intelli-php-vscode devsense.phptools-vscode devsense.profiler-php-vscode eamodio.gitlens esbenp.prettier-vscode firsttris.vscode-jest-runner flowtype.flow-for-vscode fogio.jetbrains-color-theme formulahendry.code-runner hashicorp.terraform k--kato.intellij-idea-keybindings mgmcdermott.vscode-language-babel mhutchie.git-graph ms-azuretools.vscode-containers ms-azuretools.vscode-docker ms-python.debugpy ms-python.python ms-vscode-remote.remote-containers narasimapandiyan.jetbrainsmono opentofu.vscode-opentofu paragdiwan.gitpatch redhat.java specstory.specstory-vscode vitest.explorer vscjava.vscode-gradle vscjava.vscode-java-debug vscjava.vscode-java-dependency vscjava.vscode-java-pack vscjava.vscode-java-test vscjava.vscode-maven wallabyjs.console-ninja xdebug.php-debug" | xargs -n 1 cursor --install-extension
```
