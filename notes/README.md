# Session notes

Before you can interact with the code in this folder, you must either [clone](https://help.github.com/articles/cloning-a-repository/) or [download](https://github.com/txsmith/delft-haskell-study-group/archive/master.zip) this repository on your own machine.


## Setup your editor with highlighting
To try the code and samples in this folder, do the following:
  - Install [VS Code](https://code.visualstudio.com/) with the following extension:
    - [Haskell Syntax Highlighting](https://marketplace.visualstudio.com/items?itemName=justusadam.language-haskell)

If you have any questions about this, place a message in the Slack!

## Interacting with the exercise code
Running GHCi:
- Open a command line in this folder (`haskell-study-group/notes`)
- Run `stack ghci`
- All modules present in the `src` folder are automatically loaded.

## Altering your GHCi prompt
When you run `stack ghci` with the default prompt, GHCi will print all loaded modules every time you enter an expression. If you're like me and dislike this behavior, you can alter what GHCi prints as prompt for every expression.

Run the following whenever you enter a new GHCi session:
```
:set prompt "λ > "
```
You can make this the default behavior by creating a file in your home directory named `.ghci` with the following contents:
```
p
```