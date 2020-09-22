# homework_template

Contains a LaTeX template for typesetting assignments and problem sets at University of Queensland.

## Installation and basic settings

### Install LaTeX distribution

It is **highly recommended** you install [TinyTex](https://yihui.name/tinytex/) as a lightweight LaTeX distribution. You probably only need a subset of packages anyway!

- Option 1: Install packages using 'tlmgr'

After installing TinyTex execute this command:

```{R}
tinytex::tlmgr_install(c('catchfile','enumitem','fancyhdr','filehook','fvextra','ifplatform','lineno','lm-math','makecmds','minted','polyglossia','tex','unicode-math','xcolor','xstring','tcolorbox','pgf','environ','parskip','adjustbox','collectbox','eurosym','ucs','titling','ulem','jknapltx','rsfs','pdflscape','upquote','amscls','mathtools','trimspaces','transparent','footmisc'))
```

- Option 2: Let TinyTex do the work!

Check use of 'parse_packages' or 'parse_install', and let TinyTex helper functions do the work!

### For Visual Studio Code users

1. Install [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) extension
2. Update your settings.json file with the latex workshop recipes and tools [found here](.vscode/settings.json)
3. Reload VS Code window.
4. Build your TeX file!