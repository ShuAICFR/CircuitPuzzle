# 电路维修 - 管理员“技忆”恢复训练 v1.1.7

> **《明日方舟：终末地》同人逻辑解谜小游戏**  
> *Arknights: Endfield Fan-Made Logic Puzzle Game*  
> 基于官方“源石电路修复”玩法二次创作

---

## 🧩 背景故事 | Background

在终末地的工业废墟中，源石电路的维护是管理员日常工作的重要部分。本作将官方“源石电路修复”（又名“电路模块修复”）中的**网格填图解谜**核心玩法提炼为独立的思维训练工具，帮助玩家熟悉几何堆叠与行列计数逻辑。

*In the industrial ruins of Endfield, repairing Originium circuits is a routine yet critical task. This fan game distills the core **grid-filling puzzle** mechanic into a standalone brain-training tool, designed to help players master shape placement and row/column counting logic.*

---

## 🎮 玩法还原 | Gameplay

高度还原官方“源石电路修复”的**拖拽旋转、填满网格**操作：

- **网格槽位**：主界面显示 N×N 的电路网格，需要精确填满指定区域
- **几何图形**：多种形状的模块（直线、L 形、T 形、十字等）需要拖拽到正确位置
- **旋转操作**：按 `R` 键或右键旋转模块方向
- **行列计数**：每个颜色（最多三色）独立统计行/列已填格子数，需与目标值一致
- **管理员辅助**：游戏内提供“提示”功能，高亮可能正确的摆放位置（绿色半透明）

> 官方场景中的“战斗破损”与“自然老化”被简化为障碍格，无法放置模块。

---

## ✨ 特色功能 | Features

- 🧠 **10级难度** | 10 Difficulty Levels：从“无脑”到“终焉”，复现官方从基础堆叠到色序约束的难度演进
- 🎨 **三色模式** | Single / Dual / Triple Color Modes：模拟后期“同色相邻才能稳固”的色块匹配机制
- 💡 **管理员辅助** | Admin Assist (Hint)：一键显示可能正确的格子位置
- 📱 **手机 & 桌面双端适配** | Mobile & Desktop：自动切换布局，手机端支持触摸拖拽
- 💾 **存档加密** | Encrypted Save/Load：进度可保存为二进制文件，支持跨设备迁移
- 🗺️ **地图导入/导出** | Map Import/Export：可自制或分享自定义谜题
- 📖 **方块图鉴** | Shape Collection：查看所有基础形状及其出现难度

---

## 🕹️ 操作指南 | Controls

### 桌面端
- **拖放**：鼠标按住候选方块拖至网格
- **旋转**：拖拽时按 `R` 键或右键点击网格
- **移除**：点击已放置的方块可将其拿起
- **提示**：点击“提示”按钮高亮可能位置

### 手机端
- **选择方块**：点击底部候选区选中（高亮边框）
- **放置**：点击网格空白处预览，再点“放置”确认
- **重新拿起**：点击已放置方块进入预览调整
- **菜单**：左上角 ☰ 按钮可拖拽移动，点击打开功能菜单

---

## 🛠️ 技术实现 | Tech Stack

- 纯前端：HTML + CSS + JavaScript (ES6)
- 谜题生成：对称填充 + 贪心分解算法
- 存档加密：异或加密存储为二进制文件
- 响应式布局：弹性网格 + 动态字号调整

---

## 📥 本地运行 | Run Locally

直接浏览器打开 `index.html` 即可，无需服务器。点击游戏内“📄 下载离线版”可保存完整游戏文件。

---

## ⚖️ 许可证 | License

本项目采用 [MIT License](LICENSE)，自由使用、修改和分发，请保留原作者署名。

---

## 👥 社区 & 反馈 | Community

- **作者**：轮椅工作室-涵吾珑
- **QQ交流群**：754973653（电路维修程序交流群）
- 欢迎提交 Issue 或 Pull Request 改进游戏

---

*本作品为《明日方舟：终末地》同人创作，基于官方“源石电路修复”玩法二次开发，与官方无关。*  
*This is a fan-made project inspired by the "Originium Circuit Repair" gameplay from Arknights: Endfield, not affiliated with official.*
