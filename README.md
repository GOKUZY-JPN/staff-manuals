# GOKU TRIP スタッフマニュアル

GOKU TRIP ガイドスタッフ専用のマニュアルポータルです。

## フォルダ構成

```
staff-manuals/
├── index.html                          # トップページ（マニュアル一覧）
├── railway.toml                        # Railway 静的サイト設定
└── manuals/
    └── fushimi-inari-night/
        ├── index.md                    # マニュアル本文（Markdown）← ここを編集
        ├── manual.html                 # 表示用HTML（触らない）
        └── images/                     # ツアー写真
            └── *.jpg
```

## マニュアルの更新方法

`manuals/[ツアー名]/index.md` を編集してGitHubにpushするだけで自動反映されます。

## 新しいマニュアルの追加

1. `manuals/` 以下に新フォルダを作成
2. `index.md`（本文）と `manual.html`（既存からコピーして調整）を配置
3. `index.html` のマニュアル一覧にカードを追加

---
© GOKU TRIP 株式会社 — 社内資料
