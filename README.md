typescript勉強会用
===

## 環境構築手順
npm -v
npm install -g typescript
tsc --version
npm install -g typings
npm install -g tslint

npm init -y
tsc --init

tsconfig.json→sourceMapのコメントアウトを戻す
ターミナル→規定のビルドタスクの構成→tsc: ビルド - tsconfig.json
tasks.json→"label": "build"を追加

デバッグ→構成の追加→Node.js
launch.json→"preLaunchTask": "build" を追加


