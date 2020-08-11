# D&D用リポジトリ

## ユドナリウム

https://udonarium.app/

## ユドナリウムのキャラクタを更新する方法

`adoran_lvXX`ディレクトリの`data.xml`を編集

zip化

```
zip -r adoran.zip adoran_lvXX/
```

adoran.zip をユドで読み込み

**注意** いきなり `adoran.zip` を読み込んでも反映できない。`xml_アドラン_2020-08-10_1857.zip`を読み込んでから、`adoran.zip`を読み込むと読み込める(なぜかわからない)。
**注意** XMLの書式エラーで読み込めないことがある。厄介なことに特に明確なエラーは出力されないので、注意。

