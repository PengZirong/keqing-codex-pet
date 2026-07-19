# 刻晴 · Codex `/pet`

为 Codex `/pet` 制作的刻晴人形动画角色，提供经典版与 Q 版，可任选其一或同时安装。

| 经典版 | Q 版 |
|:---:|:---:|
| <img src="variants/classic/previews/idle.gif" width="180" alt="经典版刻晴待机动画"> | <img src="variants/chibi/previews/idle.gif" width="180" alt="Q 版刻晴待机动画"> |
| 接近角色原始比例 | 约 1.6–1.8 头身，支持 16 个注视方向 |

## 安装

经典版：

```bash
mkdir -p ~/.codex/pets/keqing
cp variants/classic/pet.json variants/classic/spritesheet.webp ~/.codex/pets/keqing/
```

Q 版：

```bash
mkdir -p ~/.codex/pets/keqing-chibi
cp variants/chibi/pet.json variants/chibi/spritesheet.webp ~/.codex/pets/keqing-chibi/
```

安装后，在 Codex 中通过 `/pet` 选择「刻晴」或「刻晴·萌版」。

> 非官方同人项目。《原神》及刻晴相关权利归其权利人所有。
