# vgo-manual

#go言語のパッケージ管理方法（windows版）

### バージョンの確認
```
go version 
# go version go1.11以上でないならアップデート
```
[インストーラ](https://golang.org/dl/)  
※以前のバージョンはアンインストールしておくべし


### 環境変数の設定
```
set GO111MODULE=on
#デフォルトはauto
#その場合、go: modules disabled inside GOPATH/src by GO111MODULE=auto; see 'go help modules'　のようなエラーが出る
```
### vgoの使用
```
cd %GOPATH%\src\任意のプロジェクトパス
go mod init
#go.modが作成される
```
  
