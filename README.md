<p align="center">
  <img src="./assets/banner.svg" alt="XXD Panel 004 项目横幅" width="1200">
</p>

<div align="center">

# 🦁 XXD Panel 004

### 从一个可信的现实场景，提炼出收藏级的现代主题线描海报

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Four Modes](https://img.shields.io/badge/Modes-4-d75d32?style=flat-square)](#四种输出共享同一种现实线描逻辑)
[![Raster Output](https://img.shields.io/badge/Output-PNG-3c6f67?style=flat-square)](#边界与信任)

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> 在地现实 · 精准单线 · 几何透视 · 主题配色 · 城市品牌文字

XXD Panel 004 是一个面向 Codex 与兼容 Agent 的图像生成 Skill。它接受主题、地点、地址、坐标或参考图：先建立一幅完整、统一、真实且有日常温度的现实场景，再从同一场景中提炼最有辨识度的天际线、街道界面、招牌节奏、交通设施、橱窗关系、人群状态或主题结构，转化为纤细准确、透视清楚、安静现代的线描海报。

画面不复制照片表面，而是从源图事实中找到一个聪明、轻巧、可回看的视觉转化。它融合现代主义编辑插画、包豪斯秩序、绘本温度和时装速写的松弛感；文字像画者顺手留下的克制手写注记，而不是后来贴上去的广告标题。

## 为什么需要 004

普通“城市海报”很容易退化成地标拼贴、明信片夕阳、旅游贴纸和通用天际线；主题只剩名称，任何城市都能互换。

004 的顺序完全相反：

```text
确认主题与可靠事实 → 建立一幅统一的现实场景定调图 → 锁定三个以上在地或主题线索 → 用精准单线与几何透视提炼 → 从气候、光线、材料和文化情绪推导配色 → 把标题与地点信息纳入同一网格
```

如果换成另一个城市或主题，现实场景、线描结构、透视、当地文字、配色和文案仍然成立，这张图就不属于 004。

## 004 的视觉契约

- **可信现实场景：** 参考图、地址、坐标和可靠事实优先；城市元素在同一空间自然共生，不拼贴景点、不杜撰招牌。
- **主题专属识别：** 至少保留三个在地或主题线索，例如天际线、街道方向、立面开口、招牌节奏、交通设施、人群状态或核心结构。
- **精准线描转译：** 用纤细单线、清楚透视、遮挡关系和适度抽象提炼，而不是逐边描摹或套图标。
- **有秩序的细节：** 通过线密度、间距、重叠、留白和少量局部压重形成丰富度，不做写实明暗。
- **服务结构的几何：** 水平基线、纵向构成线和透视辅助线只用于对齐、层级与节奏。
- **主题专属配色：** 单色或极少量色彩来自气候、光线、时间、材料、历史、商业、饮食、自然与情绪。
- **收藏级文字系统：** 一个清晰主标题与零至三条可靠辅助信息共同进入网格；当地语言、地址、坐标、年份和店招不得编造。

## 样张 · 来自 X

> [小小东（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2089972269724619259) · 2026-08-19<br>
> GPT2 x 转绘 x 规则线条 x 美学提示词 x VOL.004

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2089972269724619259"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 004 样张 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2089972269724619259"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 004 样张 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2089972269724619259"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 004 样张 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2089972269724619259"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 004 样张 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2089972269724619259">查看原推文与完整提示词 →</a></p>

这些样张用于展示 004 的美学动机，不会把样张中的主体、构图、配色、文案或旧画幅变成生成参考或当前默认值。

## 四种输出共享同一种现实线描逻辑

四种模式支持单选或多选。可回复 `1`、`1+3`、`1、2、4` 或 `全部`；Skill 去重后按 1→4 执行。每种模式独立输出并进入独立子文件夹，不制作总图；`全部` 每张原图得到 7 个 PNG（前三种各 1 张＋壁纸 4 张）。尺寸可在同一回复中按模式标注，未标注普通模式按源图适配；文案默认跨所选模式共用，也可按模式单独指定。

| 模式 | 尺寸逻辑 | 成品 |
| --- | --- | --- |
| `top-bottom` | 参考图／定调图自适应 | 上方完整现实场景，下方 004 现代线描设计；两块同尺寸，严格 50/50 |
| `left-right` | 参考图／定调图自适应 | 左侧完整现实场景，右侧 004 现代线描设计；两块同尺寸，严格 50/50 |
| `design-only` | 参考图／定调图自适应 | 只显示线描设计，不显示现实场景；沿用参考图或定调图比例和尺寸 |
| `wallpaper-pack` | 四种设备尺寸 | 分别输出手机、iPad、电脑、儿童手表四张 PNG |

用户精确尺寸 > 指定比例或用途 > 参考图／现实定调图自适应。只有主题时必须先确定画幅，再生成现实定调图。原始 `004.md` 里的 3:4 不会成为静默默认值。

双联模式的摄影区域保持真实，只允许克制调色和必要的环境扩展。纯设计版与壁纸仍以照片为事实依据，但不显示原片。

### 四端壁纸：连贯或独立

壁纸没有静默尺寸默认。可选择常用预设——手机 `1440×3200`、iPad `2048×2732`、电脑 `3840×2160`、儿童手表 `1024×1024`——也可逐设备自定义。

- **连贯套装（推荐）：** 先生成并验收 iPad 线描定调图，另外三张都参考同一现实场景＋同一线描定调图，分别重新构图。
- **四张独立：** 每张只参考同一现实场景定调图，可探索不同的线描取舍、透视密度、留白与标题网格。

连贯不等于裁切。四张壁纸始终分别生成、分别构图、分别验收，也不会按 iPad→手机→电脑→手表顺序垫图造成漂移。

## 文字是城市品牌式的信息骨架

正式生图前，先选择自动文案、自定义文案或无文字。有文字时还要指定目标语言或地区。

自动文案以用户主题形成一个明确主标题；只有可靠时才加入当地语言、国家／地区、地址、坐标、编号、年份或一句极短说明。

默认只有一个标题；只有确有信息价值时才增加零至两条短注释，不会为了显得高级而编造编号、年份、坐标或档案标签。文案仍需通过换图测试。

用户提供最终成稿时逐字保留。用户提供的是方向或可编辑草稿时，才会在保留受众、目的、必备词、语气和潜台词的前提下专业深化。

语言遵循目标受众，而不是用户下指令时使用的语言：

```text
目标市场或受众 > 指定成品语言 > 用户方向语言；都不明确时生图前询问
```

日本版使用自然日语，韩国受众使用自然韩语与正确空格，英国版使用英式英语，阿拉伯语版默认使用自然的现代标准阿拉伯语和真正的从右到左排版。字体也会转译为当地文字系统中自然、略带手写温度的字形，而不是把拉丁字体规则生硬套过去。

## 精确拼版交给代码，作品交给图像生成

图像模型负责现实场景定调、在地线索提炼、精准单线、几何透视、细节节奏、主题配色和文字网格。`scripts/compose_panel.py` 只负责画布规划、精确 50/50 位图拼合、最终尺寸和审计，不会用程序绘图伪造成品。

```bash
python3 scripts/compose_panel.py --plan --layout top-bottom --source photo.png
python3 scripts/compose_panel.py --plan --layout left-right --size 2560x1440
python3 scripts/compose_panel.py --audit result.png --layout design-only --size 2048x2048
```

精确上下画布的总高度必须为偶数，精确左右画布的总宽度必须为偶数。Skill 不会静默修改用户指定的像素。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-004.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-004" ~/.codex/skills/xxd-panel-004
```

Claude Code 用户可以把同一目录链接到 `~/.claude/skills/xxd-panel-004`。安装后重新启动 Agent 会话。

```text
$xxd-panel-004
把这张照片做成左右双联，文案由你根据照片内涵创作，使用自然韩语。
```

只给主题或上传参考图都可以调用。Skill 会先询问一个或多个模式、主题输入所需画幅与文字设置；选择壁纸时还会确认连贯或独立以及设备尺寸。

完整规范：

- [Skill 工作流](SKILL.md)
- [中文完整提示词](references/xxd-panel-004-prompt.zh-CN.md)
- [英文完整提示词](references/xxd-panel-004-prompt.en.md)
- [原始风格提示词](references/004-source.md)

## 边界与信任

- 每张照片只在自己的任务中使用，不借用其他输入、旧成品或样张里的主体、颜色、文案和构图。
- 每次调用都创建新的任务子文件夹；相同原图和参数也要重新生成，旧成品不能冒充当前任务。
- 最终交付为 PNG 位图，不是 SVG、HTML、Canvas 或程序绘图替代品。
- 已配置位图桥接只返回脱敏状态，不显示供应商、端点、请求头、凭据、提示词或服务器响应正文。
- 每个所选普通模式各返回一张；若选择 `wallpaper-pack`，再返回四张独立壁纸。选择 `全部` 时每张原图共返回 7 个 PNG，分处四个同级模式文件夹，绝不生成拼贴总览。

本地拼版需要 Python 3 和 Pillow。安全位图桥接使用 Python 3.11+ 的 `tomllib`。图像生成仍需要主机 Agent 的内置位图能力或已经配置好的兼容位图路径。

## 项目结构

```text
xxd-panel-004/
├── SKILL.md
├── README.md / README.en.md / README.ja.md / README.ko.md / README.ar.md
├── agents/openai.yaml
├── assets/
│   ├── banner.svg
│   └── examples/（未来本地样张占位）
├── scripts/
│   ├── compose_panel.py
│   └── configured_imagegen.py
└── references/
    ├── xxd-panel-004-prompt.zh-CN.md
    ├── xxd-panel-004-prompt.en.md
    └── 004-source.md
```

## 关于 XXD

XXD 是小小东的品牌名称缩写。项目由 [@xiaoxiaodong01](https://x.com/xiaoxiaodong01) 创建并维护。

## 服务与会员

### 深度咨询 · 299 元/小时

Skills 使用的一对一深度咨询按 299 元/小时收费。请通过下方微信二维码联系小小东预约。

### 小小东 Skills 用户交流群 · 入群 99 元

一次支付 99 元加入用户交流群，用于交流工作流、作品与互助；不包含按小时的一对一深度咨询。扫码后请备注“Skills 用户交流群”。

### 知识星球＋成员提示词库 · 699 元/年

[知识星球](https://wx.zsxq.com/group/15554814142882)与[小小东成员提示词库](https://vip.xiaoxiaodong.ai/)是同一份会员权益：**一次年费同时开通两边，无需重复付费。**

1. 在[知识星球](https://wx.zsxq.com/group/15554814142882)开通后，微信联系小小东领取成员提示词库兑换码。
2. 在[成员提示词库](https://vip.xiaoxiaodong.ai/)自助开通后，微信联系小小东邀请进入知识星球。

<p align="center">
  <a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="小小东付费服务微信二维码" width="320"></a>
</p>

<div align="center">

**先把地方看真，再用最少的线把它留下。**

</div>

---

<div align="center">
  <h2>☕ 为开源项目赞助算力</h2>
  <p>如果这个项目为你节省了时间，可以通过微信或支付宝赞助后续测试与生成算力。</p>
  <table>
    <tr>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="小小东微信算力赞助二维码" width="180"></a><br>
        <strong>微信算力赞助</strong>
      </td>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="小小东支付宝算力赞助二维码" width="180"></a><br>
        <strong>支付宝算力赞助</strong>
      </td>
    </tr>
  </table>
  <p><sub>赞助完全自愿，不会改变这个开源项目的使用权限。</sub></p>
</div>
