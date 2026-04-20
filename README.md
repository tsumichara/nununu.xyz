# tsumichara LP — nununu.xyz

## フォルダ構成

```
/
├── index.html       ← LP本体
├── images/
│   ├── hero.jpg     ← heroセクション背景
│   ├── kaze.jpg     ← KAZE Project
│   ├── origin.jpg   ← THE ORIGIN
│   ├── wawwd.jpg    ← wawwd
│   ├── aonagi.jpg   ← AONAGI 1st
│   ├── banana.jpg   ← BANANA X
│   ├── plausible.jpg← Plausible Series
│   └── diffusion.jpg← Diffusion Model / GAN
└── README.md
```

## 作品を追加する手順

1. `images/` フォルダに画像を追加（例: `new-work.jpg`）
   - 推奨サイズ: 横900px以上、JPEG
   - ファイル名はアルファベット・ハイフンのみ

2. `index.html` を開き、`works-grid` 内のコメントテンプレートをコピー

3. 以下のブロックを貼り付けて内容を書き換える：

```html
<article class="work-box">
  <img class="work-img" src="images/new-work.jpg" alt="作品名" />
  <div class="work-meta">2025 / 形態</div>
  <h4>作品タイトル</h4>
  <p>どんな課題・依頼から始まったか。</p>
  <div class="result">
    <p><strong>実績・解決した課題：</strong>成果の説明。</p>
  </div>
</article>
```

4. GitHub にpushすればGitHub Pagesに自動反映

## GitHub Pages の設定

Settings → Pages → Source: `main` branch, `/ (root)` を選択
