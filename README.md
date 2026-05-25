# 3D Object Play

Blenderで作ったGLBをスマホ/PCのブラウザで動かして見られる、GitHub Pages向けの静的サイト。

## 使い方

`index.html` を開くと表示できます。

モデルを増やす時は、GLBを `assets/models/` に入れて、`index.html` 内の `models` に追加します。

```js
{ name: "表示名", file: "assets/models/your-model.glb" }
```

## GitHub Pagesで公開する時

1. GitHubで新しいリポジトリを作る
   - おすすめ名: `3d-object-play-web`
   - `Public` にすると無料のGitHub Pagesで公開できます
2. このフォルダの中身をアップロードする
   - `index.html`
   - `README.md`
   - `assets/` フォルダ
3. GitHubの `Settings > Pages`
4. `Deploy from a branch`
5. Branchを `main`、Folderを `/root` にする
6. 表示されたURLをスマホで開く

公開URLはだいたいこの形になります。

```txt
https://あなたのGitHub名.github.io/3d-object-play-web/
```

## 現在入っているモデル

- `assets/models/baked-hand.glb`
- `assets/models/hand-draft.glb`
- `assets/models/blue-car.glb`
- `assets/models/project-small.glb`
