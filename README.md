# devtools
Setup environment for my personal development tools

##Code Editor

02.24.2017 - Today i'm start using [Visual Studio Code](https://code.visualstudio.com) in replacement to Sublime Text, with [Monokai Dark Soda](https://marketplace.visualstudio.com/items?itemName=AdamCaviness.theme-monokai-dark-soda) color, also a customized [React Code Snippet](https://github.com/alessh/vscode-react).

###Install Monokai Color Theme

```
Visual Studio Code -> File -> Preferences -> Color Theme -> Find more in Marketplace...
```
Search for Monokai Dark Soda and install it, them reload VSCode to take effect.

###Install React Code Snippet

```
npm install -g vsce
git clone https://github.com/alessh/vscode-react.git
cd vscode-react
vsce package
```

Under VSCode type <code>type CRTL + SHIFT + P</code> and search for:

```
Extensions: Install from VSXI... 
```

Open file <code>ReactSnippets-1.2.1.vsix</code> under <code>vscode-react</code> folder and reload to take effect.

More about Publishing Tool of VSCode Extensions can be found [here](https://code.visualstudio.com/docs/tools/vscecli) and [here](https://code.visualstudio.com/docs/customization/themes) for customize color themes.

To publish changes in code snippets just upload a vsxi file to yours [Marketplace Account](https://marketplace.visualstudio.com/manage/publishers/alessh)
