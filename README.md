# 小小镜像 Agent (Little Mirror Agent)

> **在安全沙盒中映射你的意图，再触碰现实。**
> *Mapping intent in sandbox before touching reality.*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform: Windows](https://img.shields.io/badge/Platform-Windows-blue.svg)]()

## 🪞 项目理念 / Philosophy

现在的 Agent 太像“黑盒”，直接操作现实，风险不可控。
Current Agents are like "black boxes", operating reality directly with uncontrollable risks.

**小小镜像**希望 Agent 是现实的一面**镜子**：
**Little Mirror** wants the Agent to be a **mirror** of reality:

1.  **映射 (Reflection)**：通过 UI 树感知环境，而非盲目猜测。
    *Perceive environment via UI Tree, not blind guessing.*
2.  **隔离 (Isolation)**：在沙盒中预演操作，确保安全第一。
    *Rehearse operations in sandbox, ensuring safety first.*
3.  **演化 (Evolution)**：代码是死的，思想是活的。我们提供一个“镜像”参考，世界可以随意修改它。
    *Code is dead, ideas are alive. We provide a "mirror" reference; the world can modify it freely.*

## 🛠️ 核心架构 / Core Architecture

- **🛡️ 安全底座 (Security)**：规则沙盒 + 权限管理 + 物理隔离
- **👁️ 环境感知 (Perception)**：Windows UI 树读取 + 坐标提示
- **🧠 记忆扩展 (Memory)**：基于固定 Schema 的压缩记忆
- **❓ 主动好奇 (Curiosity)**：基于规则的主动询问机制

## 🚀 快速开始 / Quick Start

### 环境要求 / Requirements
- Python 3.9+
- Windows 10/11
- 本地大模型 (如 Ollama) 或 API Key

### 安装 / Install
```bash
git clone https://github.com/你的用户名/little-mirror-agent.git
cd little-mirror-agent
pip install -r requirements.txt

python main.py --task "帮我打开记事本"



关于本项目 / About
这是一个开源实验。 This is an open-source experiment.

我们不追求完美，不追求商业闭环，只希望为“安全可信的桌面 Agent"提供一种可能的实现路径。 We do not pursue perfection or commercial closure, only hoping to provide a possible implementation path for "Safe & Grounded Desktop Agent".

如果你认同这个方向，欢迎 Fork、修改、甚至推翻重来。 If you agree with this direction, welcome to Fork, modify, or even overturn it.

结构变不变没关系，发展成什么样没关系，只要它能给这个世界带来一点不同的思考，就足够了。 It doesn't matter if the structure changes or how it develops, as long as it brings a different thought to this world, it is enough.

📄 许可证 / License
MIT License - 请随意使用，随意修改。 MIT License - Feel free to use and modify.

