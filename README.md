# homework_template

Contains a LaTeX template for typesetting assignments and problem sets at University of Queensland.

## Installation and basic settings

### Install LaTeX distribution

It is **highly recommended** you install [TinyTex](https://yihui.name/tinytex/) as a lightweight LaTeX distribution. You probably only need a subset of packages anyway!

- Option 1: Install packages using 'tlmgr'

After installing TinyTex, execute this command in R:

```
tinytex::tlmgr_install(c('adjustbox','amscls','catchfile','collectbox','enumitem','environ','eurosym',
  'fancyhdr','filehook','footmisc','fvextra','ifplatform','jknapltx','lineno','lm-math','makecmds',
  'mathtools','minted','parskip','pdflscape','pgf','polyglossia','rsfs','tcolorbox','tex','titling',
   'transparent','trimspaces','ucs','ulem','unicode-math','upquote','xcolor','xstring'))
```

Or if you prefer installing using 'tlmgr':

```
tlmgr install adjustbox amscls catchfile collectbox enumitem environ eurosym fancyhdr filehook 
  footmisc fvextra ifplatform jknapltx lineno lm-math makecmds mathtools minted parskip pdflscape pgf 
  polyglossia rsfs tcolorbox tex titling transparent trimspaces ucs ulem unicode-math upquote xcolor xstring
```


- Option 2: Let TinyTex do the work!

Check use of 'parse_packages' or 'parse_install', and let TinyTex helper functions do the work!

### For Visual Studio Code users

1. Install [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) extension
2. Update your settings.json file with the latex workshop recipes and tools [found here](.vscode/settings.json)
3. Reload VS Code window.
4. Build your TeX file!
