# 納車タスク管理ツール（スタッフ用）

## ファイル構成

```
index.html        ← スタッフが使うメインツール
calendar.json     ← 管理者が出力したカレンダーデータ（要更新）
README.md         ← このファイル
```

## 使い方

1. `index.html` をブラウザで開く
2. タスクを登録・管理する
3. カレンダーデータは `calendar.json` から自動読み込みされます

## カレンダーデータの更新

管理者が `admin-calendar.html` で設定を更新し、  
出力した `calendar.json` をこのフォルダに上書きしてください。

> ※ `calendar.json` がない場合はブラウザのローカルデータを使用します。

## GitHub Pages での公開手順

1. このリポジトリを GitHub にアップロード
2. Settings → Pages → Branch: main / root を選択
3. 公開URLにアクセスして使用
