# rusty-umbrella

## Setup
### install extensions ([list of all project extension](.vscode/extension.txt))
- bash compatible (linux/mac)
	```bash
	for pkg in $(cat .vscode/extension.txt);
		do code --install-extension "$pkg";
		done;
	```
- powershell compatible (windows)
	```powershell
	Get-Content extensions.txt | ForEach-Object {code --install-extension $_}
	```
