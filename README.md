# Scoop

- [Scoop](https://scoop.sh/)
- [Wiki](https://github.com/ScoopInstaller/Scoop/wiki)
    - [App Manifests](https://github.com/lukesampson/scoop/wiki/App-Manifests)


## Manifest更新

```powershell
# カレントディレクトリを当ファイル位置にして下記実行
> $checkver="C:\Users\$env:USERNAME\scoop\apps\scoop\current\bin\checkver.ps1 * -dir . -u"; Invoke-Expression $checkver
```
