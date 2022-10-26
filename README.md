# Scoop

- 書き方: <https://github.com/lukesampson/scoop/wiki/App-Manifests>
- Manifest更新  
    PowerShellでカレントディレクトリを当ファイル位置にして、下記実行  
    `$checkver="C:\Users\$env:USERNAME\scoop\apps\scoop\current\bin\checkver.ps1 * -dir . -u"; Invoke-Expression $checkver`


<!-- cSpell:word checkver -->
