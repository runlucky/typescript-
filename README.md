typescript勉強会用
===

## 環境構築手順
npm -v
npm install -g typescript
tsc --version
npm install -g typings
npm install -g tslint

## プロジェクトでの環境構築
npm init -y
tsc --init

tsconfig.json→sourceMapのコメントアウトを戻す
ターミナル→規定のビルドタスクの構成→tsc: ビルド - tsconfig.json
tasks.json→"label": "build"を追加

デバッグ→構成の追加→Node.js
launch.json→"preLaunchTask": "build" を追加

## uuidを使うには
npm install uuid
typings init
typings install uuid --save --ambient
npm i @types/node