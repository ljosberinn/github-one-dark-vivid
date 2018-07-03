# Github VS Code One Dark Vivid with Fira Code

[Chrome Web Store](https://chrome.google.com/webstore/detail/github-vs-code-one-dark-v/ifhihbeapkbahaelfppkncgmmmeidapl)

changes Githubs code appearance to resemble One Dark Vivid of VS Code as closely as possible, built upon vovanmix/github-dark-theme

![img](https://raw.githubusercontent.com/ljosberinn/github-one-dark-vivid/master/img.png 'image')

requires https://github.com/tonsky/FiraCode installed locally


If you wish more colors to be added, please open a PR.

Fonts need to be added to [/src/code.less line 5](https://github.com/ljosberinn/github-one-dark-vivid/blob/master/src/code.less), with a fallback for macOS/Windows (different naming for the same font)

# Git started

```sh
git clone https://github.com/github-one-dark-vivid

yarn install

yarn run build
```

# Credits

built upon [Github Dark Theme @ Vovanmix](https://github.com/vovanmix/github-dark-theme)
