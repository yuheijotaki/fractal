# Fractal test



スタイルガイドジェネレーターを使う必要がありそうなので調べてみました。

候補は、

- Fractal https://fractal.build/
- aigis https://aigis-styleguide.github.io/aigis/

のどちらかで aigis は公式日本語ドキュメントがあるので良かったのですが、Fractal のほうがUIが良さそうなのと最近でもアップデートが行われているので Fractal を試してみました。



## 導入

基本は Qiita の [この記事](https://qiita.com/fujihiko/items/70f985fbc4bb32c505a1) を参考にインストール、起動しました。



## コマンド







### ローカル環境で確認

```bash
$ fractal start --sync
```

**ローカルURL**

```
Local URL:      http://localhost:3000    
Network URL:    http://192.168.75.44:3000
BrowserSync UI: http://localhost:3002  
```

### 静的ファイルのビルド

```
$ fractal build
```



## 参考記事

Fractal デザインスタイルガイド 導入  
https://qiita.com/fujihiko/items/70f985fbc4bb32c505a1