# 松山福祉専門学校 授業資料 Quarto Site

## 使い方

1. このフォルダを開く
2. PowerShell / Terminal で以下を実行

```bash
quarto preview
```

## PDFの置き場所

- 福祉研究科：`files/seminar/`
- 福祉経営科：`files/theory/`

## 新しい授業を追加する場合

例：福祉研究科 第3回

1. `seminar/lesson02.qmd` をコピーして `seminar/lesson03.qmd` にする
2. PDFを `files/seminar/lesson03_xxx.pdf` に入れる
3. `seminar/index.qmd` と `_quarto.yml` にリンクを追加する
