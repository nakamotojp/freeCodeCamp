---
id: 587d774c367417b2b2512a9c
title: 为视觉障碍用户添加替代图像的文本
challengeType: 0
videoUrl: 'https://scrimba.com/c/cPp7VfD'
forumTopicId: 16628
dashedName: add-a-text-alternative-to-images-for-visually-impaired-accessibility
---



# --description --

他の課題で、`img`タグの`alt`属性を見たことがあるかもしれません。alt`テキストは、画像のコンテンツを説明し、そのテキストの代替手段を提供します。alt`属性は、画像の読み込みに失敗したり、ユーザーが見ることができない場合に役立ちます。また、検索エンジンは、画像の内容を理解して検索結果に含めるために使用します。以下にその例を示します。

``html
<img src="importantLogo.jpeg" alt="Company logo">
```

視覚障害者は、ウェブコンテンツを音声インターフェースに変換するスクリーンリーダーに頼っています。視覚障害者は、ウェブコンテンツを音声に変換するためにスクリーンリーダーを利用します。画像の場合、スクリーンリーダーは `alt` 属性にアクセスしてその内容を読み取り、重要な情報を提供することができます。

良い `alt` テキストは、画像の簡単な説明を読者に提供します。画像には必ず `alt` 属性を含める必要があります。HTML5の仕様では、これが必須とされています。

# --instructions --

Camper Catはたまたまコーディングニンジャであり、実際のニンジャでもあり、自分の知識を共有するためにウェブサイトを作っています。彼が使いたいと思っているプロフィール画像は、彼のスキルを示すものであり、サイト訪問者全員に評価されるべきものです。img`タグに`alt`属性を追加して、Camper Catが空手をやっていることを説明します。(画像の `src` は実際のファイルにリンクしていないので、表示されるのは `alt` のテキストです)。

# --hints--

img` タグには `alt` 属性が必要で、空であってはいけません。

````js
assert($('img').attr('alt'));
```

# --seed--

## --seed-contents--

```html
<img src="doingKarateWow.jpeg">.
```

# -solutions--

```html
<img src="doingKarateWow.jpeg" alt="Someone doing karate">
```

