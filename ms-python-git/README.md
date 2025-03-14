# Microsoft Python

Microsoft Dev Container 公式の Python イメージにパッケージ追加のオプションを加えた環境

Ruff で Format と Lint を行う

## Option

GitHub と連携できるよう Git をインストールするようにしています

## Environment

2025/03/14 現在

| OS | Version |
|----|---------|
| Debian | LTS | 

| Language / runtime | Version | 
|--------------------|---------|
| Python | 3.12.2 | 

| Option Package | Version |
|----------------|---------|
| Git | 2.47.1 |

| Docker | SIZE |
|--------|------|
| Image Size | 1.49GB | 

## Extensions

- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [Python Indent](https://marketplace.visualstudio.com/items?itemName=KevinRose.vsc-python-indent)
- [autoDocstring - Python Docstring Generator](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring)
- [Ruff](https://marketplace.visualstudio.com/items?itemName=charliermarsh.ruff)
- [IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)

## Note

必ず、**`devcontainer.json`** の "postCreateCommand" セクションの 'username' と commit-mail' をご自身が使用するものに修正してください<br>
**この編集をしないと、GitHub との連携が行えません**
