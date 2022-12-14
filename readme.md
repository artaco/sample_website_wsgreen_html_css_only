## はじめに

こちらはポートフォリオのリポジトリになります。

本ポートフォリオは Web 制作において基本の知識である HTML/CSS のみを使用したシンプルな PC 版 Web サイトです。

Web サイトののカンプや素材は[ウェブスタッフ](https://www.webstaff.jp/)様で提供されているものを使用しました。
[ウェブスタッフ](https://www.webstaff.jp/)に会員登録をすると利用できるキャリアサポートの中に、[クリエイティブ・ワーク・ライブラリ](https://www.webstaff.jp/haken/support/library.shtml)というサービスがあります。
今回は、この中から「Web サイト：野菜宅配サービス」を選びました。

本ポートフォリオは、この Web サイトをベースにレスポンシブ対応やログイン機能を追加したり、JavaScript フレームワークなどモダンな技術を用いるなどアップデートしていく予定です。

---

## ポートフォリオ

### URL

[https://portfolio.artaco.work/website/wsgreen_html_css_only/](https://portfolio.artaco.work/website/wsgreen_html_css_only/)

### ホスティング

Xserver

## 開発環境

### OS

macOS Big Sur ver 11.7

### ブラウザ

Chrome ver 108

### エディタ

Visual Studio Code ver 1.74.0

### デザインツール

Affinity Photo ver 1.10.6

Affinity Designer ver 1.10.6

## 要件

課題資料に記載されている仕様は以下のとおり

### コンセプト

サービス申し込みの増加

### ターゲット

無農薬野菜を購入したいと考えている 20 代~50 代の女性

### 必須コンテンツ

- トップページ
- お試しセット
- はじめての方へ

### 想定ブラウザ

#### OS

Windows 8 / Windows 10

#### ブラウザ

InternetExplore 10 / InternetExplore 11 / Edge、Firefox(最新版)、Chrome(最新版)

### サイズ

横幅:980 px

### ファイル構造

- サイトマップに合わせ、ディレクトリを分割する
- ディレクトリには、内容のわかる名称をつける ※日本語での名称設定は不可
- ディレクトリには必ず index.html を置く
- 画像ファイルのディレクトリ名は images とする
- 各ページに共通して使用する画像ファイルは、一番浅いディレクトリに置く(ディレクトリ名 common とする)
- 各コンテンツで単独に使用する画像ファイルはそれぞれのコンテンツディレクトリに置く

### 使用静止画像形式

- 静止画像は GIF および JPEG、PNG 形式を原則とし、可能な範囲で容量を小さくする。
- ＜ img ＞には width,height,alt 属性を必ず指定する
- 画像の縮小拡大は行わず、等倍指定となるように素材サイズを調整する
- 画像内に文字情報がある場合、alt 指定を必ず指定する
- alt = " " の記入漏れをしないこと
- 画像の名前は必要に応じ変更する
- 数字を使う場合は 2 桁(01、02 等)

### コーディング

- タグは全て小文字で記述
- インデント方法は、サイトごとに統一する(タブを使用し、タブの大きさは半角スペース 2 文字を推奨)
- 本文中には適度にコメントタグを使用し、構造がわかるようにする

---

## パフォーマンス

### PageSpeed Insights

[PageSpeed Insights](https://pagespeed.web.dev/)による PC での表示速度測定結果（モバイル未対応のため）

![PageSpeed Insights](images/pagespeed.png)

### CSS CODE QUALITY

[CSS CODE QUALITY](https://www.projectwallace.com/css-code-quality)による CSS の評価

#### トップページ

![CSS CODE QUALITY / TOP](images/css_code_quality_top.png)

#### 初めての方へ

![CSS CODE QUALITY / OTHER](images/css_code_quality_other.png)

#### お試しセット

![CSS CODE QUALITY / OTHER](images/css_code_quality_other.png)
