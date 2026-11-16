# GYV — 小猪盖被 · 成品视频库

这里存 **小猪盖被** 已经做好的成品英语短视频，一支视频一个文件夹，方便版本管理。

生产工厂在另一个仓库（GYEVideo，Remotion 模板 + 剧集数据）；这里只放成品：
每集的视频、封面、小红书文案和一份说明（README）。

## 制作原则

**画面场景必须结合当前单词的核心含义** —— 场景就是词义本身：
小猪在舞台上把这个词"演"出来，演不出来核心意思的词，不硬塞进动作里。

## 目录

| 文件夹 | 词根 | 考试 | 单词 |
|---|---|---|---|
| [063_uni_stageplay](063_uni_stageplay/) | uni = 一 | 高考 | unite / uniform / unique / universe |
| [067_ject_stageplay](067_ject_stageplay/) | ject = 抛；投 | 四级 | project / reject / inject / eject |
| [068_mit_stageplay](068_mit_stageplay/) | mit / miss = 送；寄 | 四级 | transmit / admit / dismiss / emit（拓展） |

## 每个文件夹里有什么

- `<集数>.mp4` — 成片（1080×1920 竖屏）
- `<集数>_cover.png` — 封面图
- `文案.md` — 小红书发布文案（标题 / 正文 / 话题）
- `README.md` — 这一集的说明与版本记录

## 版本约定

- 同一集有修改时，在该集 README 的「版本记录」里加一行：日期 + 改了什么。
- 目前三集均为**无配音样片**（配乐 + 音效齐全）；正式配音版需在装有
  DASHSCOPE_API_KEY 的机器上对工厂仓库跑 `npm run produce` 后替换 mp4，
  并在版本记录里注明。
