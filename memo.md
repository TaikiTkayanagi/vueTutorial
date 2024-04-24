# インストール
* vue devToolのインストール
> https://devtools.vuejs.org/guide/installation.html


# vue CLI
## CLI
* @vue/cliはグローバルにインストールされたnpmパッケージでターミナルでvueコマンドを提供する
## CLI Service
* @vue/cli-serviceは開発依存
* package.jsonに記述されてそのnode_moduleにインストールされる
* webpackとwebpack-dev-serverの上に構築される
## CLIのインストール
```bash
npm install -g @vue/cli
```

## Reactとの比較
### 類似点
* 仮想DOMを使う
* ルーティングやグローバルの状態管理は他ライブラリに担当させる

### Vueのメリット
* Reactは関係ない子のコンポーネントを再描画しないようにPureComponent/ShouldComponentUpdateを使って最適化を行う
* vueは親子関係を意識せずに再描画のコンポーネントを正確認識する
    *
