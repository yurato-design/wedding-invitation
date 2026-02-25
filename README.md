## Wedding Invitation Demo Site

ポートフォリオ用に制作した架空のウェディング招待サイトです。
FigmaでデザインしたOGP画像やファビコンを含め、デザインからHTML/CSS実装、OGP設定、GitHub Pages公開まで一貫して制作しています。
柔らかい世界観と実務的なWeb制作フローを両立したデモ作品です。
---

## 🔗 Repository
https://github.com/yurato-design/wedding-invitation

## 🌐 Demo
https://yurato-design.github.io/wedding-invitation/

---

## 📸 Overview  
本サイトは以下の3セクションで構成されています。

- **Message**  
  新郎新婦からのメッセージを掲載。

- **Date / Access**  
  開催日時・場所を視覚的にわかりやすく表示。

- **RSVP Form**  
  出欠連絡フォーム（UIデザインのみ）。

---

## 🛠 使用技術

### Frontend
- HTML5  
- CSS3（Flexbox / メディアクエリ）  
- Google Fonts（Josefin Sans / Sawarabi Mincho）  
- srcset を用いた高解像度画像の出し分け  
- レスポンシブデザイン（max-width: 640px）

### Assets
- hero画像・装飾画像  
- OGP画像（1200×630px）  
- favicon（SVG）

---

## 📁 ディレクトリ構成
```
wedding-invitation/
├── index.html
├── 404.html
├── robots.txt
├── sitemap.xml
├── css/
│   ├── reset.css
│   └── style.css
└── images/
    ├── hero.jpg
    ├── hero_sp.jpg
    ├── hero_text.png
    ├── message_img.png
    ├── date_img.jpg
    ├── ogp.png
    └── favicon.svg
```

---

## 🎨 デザインのポイント

- **上品で落ち着いた色味**  
  ウェディングの雰囲気に合わせ、柔らかいベージュ・ホワイトを基調に構成。

- **視線誘導を意識したレイアウト**  
  メインビジュアル → メッセージ → 日付 → フォーム の流れで自然に読み進められる構成。

- **スマホ最適化**  
  PC版の横並びレイアウトをスマホでは縦並びに変更し、読みやすさを重視。

- **高解像度画像対応（srcset）**  
  Retinaディスプレイでも画像が粗くならないよう調整。

---

## 🔧 今後の改善案（任意）

- バックエンドと連携した実際のフォーム送信機能  
- アニメーションの追加  
- 多言語対応（日本語 / 英語）

---

## 📜 ライセンス
本プロジェクトは個人制作のポートフォリオ用です。  
画像素材の無断転載はご遠慮ください。


