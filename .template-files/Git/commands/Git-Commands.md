# Git Commands

Below is a list of simple and easy-touse `git` commands.

## Trouble Previewing?

1. If you are viewing this document in __[Visual Studio Code](https://code.visualstudio.com/)__ but don't see __[Markdown Preview]__ *at all*, see the __[Markdown Preview Guide]__.
2. If the __[Markdown Preview]__ is open but the __[Syntax Highlighting]__ isn't working, make sure you have the __[GitHub Markdown Preview](https://marketplace.visualstudio.com/items?itemName=bierner.github-markdown-preview)__ Extension Pack Installed
	- *You can find it under __[Workspace Recommendations](https://code.visualstudio.com/docs/editor/extension-marketplace#_workspace-recommended-extensions)__ in the __[Extensions](https://code.visualstudio.com/docs/editor/extension-marketplace#_browse-for-extensions)__ tab*

<br />

---

# Git Clone

### IMPORTANT:
 When using the `git` __[Command Line Interface]__ (regardless of the shell environment), there are two important things to keep in mind about the __[Destination Folder]__:
 1. The __Directory Name__ and the __Repository Name__ do *not* have to match.
 2. The __Destination Folder__ *must* be completely empty, or not exist at all- otherwise the command will fail with an error.

## Basic HTTPS

### Syntax
```bash
git clone https://[url].git "[destination directory]"
```

### Samples
```bash
# For MacOS & Linux Directories
git clone https://github.com/NewSpectrum/Simple-Template.git "~/dev/projects/Simple-Template"
```

```powershell
# For Windows PowerShell
git clone 'https://github.com/NewSpectrum/Simple-Template.git' "$env:UserProfile\Dev\Projects\Simple-Template"
```