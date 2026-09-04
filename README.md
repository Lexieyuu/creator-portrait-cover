# Creator Portrait Cover（自媒体活人感封面）

一个用于生成真实拍摄感、自然生活感、近距离口播感自媒体人物封面的 Codex Skill。默认输出 3:4 竖版构图，人物通常占画面高度约 70%–75%。

## 用途

- 将人物照片自然融入指定环境
- 为已有完整人物图生成匹配的真实环境
- 在只有头部信息时，保守补全肩颈和有限上半身
- 保留人物本人特征，减少抠图感、美颜感、棚拍感和 AI 感
- 输出无文字、无标题、无标语、无涂鸦，为后续自行加字预留画布

## 输入方式与三种模式

### Mode A — 人物图 + 环境图

环境图是空间基准，人物图提供身份、姿态和可见身体范围。保留环境构图，将人物进行透视、尺度、遮挡、色温和光影融合。

### Mode B — 仅人物图且身体信息足够

保留人物已有的身体裁切、姿态、手部和手持物，自动生成不抢主体的真实摄影环境。

### Mode C — 仅头部或身体信息不足

以头部作为身份锚点，只允许补全合理的脖颈、肩部、胸部或有限上半身；默认不补全完整手臂、手掌、腰部以下或复杂手势。

## 核心协议

Identity Lock、Expression/Head Pose Lock、Crop Lock、Text-Free Canvas、Body Completion、Foreground Dominance、Photographic Integration、Environment Lock、Lighting Integration，以及手部与手持物保护、活人感规则，详见 [`references/`](references/)。默认视觉语言收录在 `style-natural-talking-head.md`。

## 安装

将 `creator-portrait-cover` 目录复制到 Codex 的 skills 目录，或在支持 Skill 仓库的环境中引用该目录。安装后可用 `$creator-portrait-cover` 显式调用；默认也允许自动匹配。

## 使用示例

```text
使用 $creator-portrait-cover，把这张人物图做成 3:4 的自媒体口播封面，保留原表情、发型、服装和手持物，生成自然生活化背景；画面不要出现任何文字，我后续自己加。
```

默认风格关键词：

`自然口播感、生活化室内空间、半身中近景、人物主体突出、浅景深、背景柔焦、自然窗光、柔和漫反射、真实皮肤纹理、真实手势、轻微抓拍感、人物与环境自然融合、干净留白、无文字`

```text
使用 $creator-portrait-cover，把人物图合成到环境图中。环境作为唯一空间基准，人物占画面约 70%–75%，不要换脸或改变人物裁切。
```

## 项目结构

```text
creator-portrait-cover/
├── SKILL.md
├── README.md
├── agents/openai.yaml
└── references/
    ├── mode-a-environment-composite.md
    ├── mode-b-automatic-environment.md
    ├── mode-c-body-completion.md
    ├── protection-protocol.md
    ├── photographic-integration.md
    ├── quality-checklist.md
    └── style-natural-talking-head.md
```
