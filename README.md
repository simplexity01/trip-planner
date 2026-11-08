# Trip Planner

个人旅行规划合集。每一次出行整理成一份独立的电子旅行手册（单文件 HTML），
包含行程总览、每日路线、酒店、交通、预算、行前清单和官方信息链接，
可直接在浏览器打开，也方便打印或在手机上查看。

## 特点

- **单文件 HTML**：样式内联，无需构建、无需依赖，双击即可打开。
- **移动端适配**：响应式布局，手机浏览器直接看；同时支持打印样式。
- **内容完整**：覆盖行程、交通、住宿、预算与行前清单，出发前看这一份就够。
- **持续积累**：每个目的地一个文件，后续不断补充新的旅行规划。

## 旅行手册

| 目的地 | 天数 | 季节 | 文件 |
| --- | --- | --- | --- |
| 东京 · 富士山 · 箱根 | 7 天 6 晚 | 12 月上旬 | [tokyo_fuji_hakone_travel_guide.html](tokyo_fuji_hakone_travel_guide.html) |

### 东京 · 富士山 · 箱根（7 天 6 晚）

两人同行，从北京出发，路线为 **东京 → 河口湖 → 箱根 → 东京机场**，不走回头路。
手册包含：

- 行程总览与出行原则
- 每日详细路线（时间轴、景点、交通方式）
- 酒店推荐（东京新宿 / 河口湖 / 箱根温泉旅馆）
- 交通攻略（Suica、高速巴士、箱根周游券等）
- 两人预算参考
- 出发前检查清单
- 官方信息与快速入口

## 如何查看

1. 克隆仓库：

   ```bash
   git clone git@github.com:simplexity01/trip-planner.git
   ```

2. 用浏览器直接打开对应的 `.html` 文件即可，无需安装任何东西。

也可以在 GitHub 上直接点击 HTML 文件预览，或后续配置 GitHub Pages 在线访问。

## 目录与命名约定

每份旅行手册放在仓库根目录，按「目的地」命名，方便以后扩展：

```
trip-planner/
├── README.md
├── tokyo_fuji_hakone_travel_guide.html   # 东京·富士山·箱根
└── <destination>_travel_guide.html       # 以后新增的目的地
```

命名建议：

- 文件名全部小写，单词用下划线 `_` 连接。
- 多城市路线按行程顺序拼接，例如 `osaka_kyoto_nara_travel_guide.html`。
- 单一城市可简写，例如 `taipei_travel_guide.html`。
- 同一目的地多次出行，可在末尾加年份，例如 `hokkaido_travel_guide_2027.html`。

## 新增一份旅行规划

1. 复制现有 HTML 文件作为模板。
2. 修改标题、封面信息、行程章节与表格内容。
3. 按命名约定保存为新的 `<destination>_travel_guide.html`。
4. 在本 README 的「旅行手册」表格中登记一行。
5. 提交并推送：

   ```bash
   git add -A
   git commit -m "Add <destination> travel guide"
   git push
   ```

## 说明

- 手册中的时间、价格和交通信息为规划参考，并非已购票或已预约内容。
- 出发前请以交通运营方和景点的官方公告为准（尤其是季节性停运、检修等安排）。
