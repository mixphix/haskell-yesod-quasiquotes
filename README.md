# haskell-yesod-quasiquotes

Support for [Yesod](https://www.yesodweb.com/)'s Shakespeare template syntax highlighting inside Haskell source files.

## Dependencies

This extension requires
[haskell-syntax-highlighting](https://github.com/JustusAdam/language-haskell)
and
[vscode-language-yesod](https://github.com/e-bigmoon/vscode-language-yesod).

## Known Issues

Cassius and route quasiquoters are not currently supported because of regex mismatching [upstream](https://github.com/e-bigmoon/vscode-language-yesod).

## Release Notes

### 0.1.0

Initial release
  - Support for (|s|w|x)hamlet, lucius, julius, and model syntax highlighting within Haskell (.hs) source files
