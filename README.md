# VST

PlantsSystem の Linux 向けプラグイン(VST)の配布用リポジトリです。

| Plugin | 概要 |
|---|---|
| **LMD649** | YMO「BGM」「テクノデリック」期のサンプラー LMD-649 をモチーフにした、リズム/サンプラー系プラグイン。液晶風UIと GACHA(パターンのランダム生成)を搭載。 |
| **KORPER** | ELECTRONIC BODY MUSIC(EBM)に特化した楽器プラグイン。 |

## Download

ダウンロードは右側の **[Releases](../../releases)** から。
ファイルは `tar.gz`(または `zip`)に固めてあるので、展開してお使いください。

## Install (Linux)

展開したプラグインを、使う形式に合わせて次のフォルダへコピーします。

| Format | Folder |
|---|---|
| VST3 | `~/.vst3/` |
| CLAP | `~/.clap/` |
| LV2 | `~/.lv2/` |

例:

```sh
tar xzf LMD649-linux.tar.gz
cp -r LMD649.vst3 ~/.vst3/
```

コピーしたあと、DAW でプラグインのスキャンをやり直してください。
Renoise(Linux)で動作を確認しています。

## Notes

- 本リポジトリは個人制作のプラグインを配布するためのものです。無保証で提供します。
- 不具合や要望は [Issues](../../issues) へ。

## Links

- Web: https://plantssystem.github.io/KOSMOS2-SITE/
- X: [@plantssystem89]([https://x.com/plantssystem](https://x.com/plantssystem89)
- GitHub: [plantssystem](https://github.com/plantssystem)

---

created by osamu/plantssystem
