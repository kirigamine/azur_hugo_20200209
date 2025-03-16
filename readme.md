# サイト(2020_02/09-2025_03-)
## 覚書
`baseURL`の確認を忘れずに。ローカル時は`/`、Page稼働時は
```config.toml
baseURL = "https://kirigamine.github.io/"
```
にする。

```config.toml
avatar = "logo.png"
```
このURLが'img/img'とか参照してないか確認する。
AIが`header.html`の修正案を提案してくれたとはいえ、パス通らないとタコがでてこない。