<div align="center">

# Hi there, I'm Zikuan Qi （綦子宽） 👋

### 🎓 PhD student @ University of Sydney · Machine Learning & Deep Learning

· 专注 机器学习 / 深度学习 / 神经网络 / 时间序列预测 / 深度推荐 / ARC-AGI

[![Profile Views](https://komarev.com/ghpvc/?username=zikuanqi&label=Profile%20views&color=0e75b6&style=flat)](https://github.com/zikuanqi)
[![Kaggle](https://img.shields.io/badge/Kaggle-Zikuan_Qi-20BEFF?style=flat&logo=kaggle&logoColor=white)](https://www.kaggle.com/zikuanqi)
[![Email](https://img.shields.io/badge/Email-ziqi5454%40uni.sydney.edu.au-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:ziqi5454@uni.sydney.edu.au)

</div>

---

## 🧑‍💻 About Me · 关于我

- 🔬 **Research · 研究方向**：高效深度网络架构（KAN × Transformer、量化 / MatMul-free）、时间序列预测、深度推荐系统、ARC-AGI 神经求解
- 🛰️ **Currently building · 正在做**：把 ARC-AGI 谜题压成极小 ONNX 网络（[NeuroGolf](https://github.com/zikuanqi/NeuroGolf)）+ KAN-Transformer 能耗预测框架
- 🌱 **Exploring · 在学**：三值 / MatMul-free 量化网络、对比学习（InfoNCE）、神经符号推理
- 🏆 **Competitions · 竞赛**：常驻 Kaggle / 天池，偏爱**防泄漏 CV** 与**多模型集成**
- 💬 **Ask me about · 可以聊**：PyTorch、ONNX 图构建、Kaggle pipeline、可复现的 ML 工程
- ⚡ **Fun fact · 冷知识**：我给自己的一篇会议论文做了「从公式到 96% 测试覆盖率」的完整复现

---

## 🛠️ Tech Stack · 技术栈

**Languages & Deep Learning · 语言与深度学习**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Lightning](https://img.shields.io/badge/PyTorch%20Lightning-792EE5?style=flat-square&logo=lightning&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![ONNX Runtime](https://img.shields.io/badge/ONNX%20Runtime-FF6F00?style=flat-square)

**ML · Gradient Boosting & Tuning · 机器学习与调参**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-9ACD32?style=flat-square)
![XGBoost](https://img.shields.io/badge/XGBoost-EB5E28?style=flat-square)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logoColor=black)
![Optuna](https://img.shields.io/badge/Optuna-7B61FF?style=flat-square)

**Data & Scientific · 数据与科学计算**

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Apps & Tooling · 应用与工程**

![Qt](https://img.shields.io/badge/PySide6%20/%20Qt-41CD52?style=flat-square&logo=qt&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logo=ruff&logoColor=black)

---

## 🚀 Featured Projects · 精选项目

| Project · 项目 | What it does · 简介 | Highlights · 亮点 |
|---|---|---|
| 🏢 **[KAN-Transformer-BECP](https://github.com/zikuanqi/Enhancing-Building-Energy-Prediction-via-KAN-Transformer-A-Multi-scale-Temporal-Learning-Approach)** | KAN × Transformer 建筑能耗预测，自有论文官方复现：多尺度时序分解 + Dynamic-Transformer 门控 + MatMul-free 三值层 + 层级 KAN 前馈 | `PyTorch` · 59 tests / **96%** cov · 9-job cross-OS CI |
| 🧩 **[NeuroGolf](https://github.com/zikuanqi/NeuroGolf)** | 用**极小 ONNX 网络**求解 ARC-AGI 谜题，在通过全部样例的前提下最小化 显存+参数；30+ 手写图求解器 | `ONNX` / `ONNX Runtime` · **62/400** tasks · 公榜 ~924 |
| 🛒 **[tianchi-E-commerce](https://github.com/zikuanqi/tianchi-E-commerce)** | 天池移动推荐：**双塔 + Transformer 行为序列**深度推荐系统，零泄漏推理，完全对齐竞赛规范 | `PyTorch Lightning` · 97 tests / **99%** cov |
| 🚀 **[Spaceship-Titanic](https://github.com/zikuanqi/Spaceship-Titanic)** | Kaggle 五模型集成（LGB / XGB / CatBoost / HGB / LR）+ 防泄漏目标编码 + logloss 加权融合 | `Optuna` · honest CV **0.8170** |
| ⏱️ **[Screen-Time-Tracker](https://github.com/zikuanqi/Screen-time-tracker)** | iOS 风格的 Windows 屏幕使用时间桌面应用：空闲检测、托盘常驻、SQLite 本地存储 | `PySide6 / Qt` · `SQLite` · `PyInstaller` |

---

## 📝 Publication · 学术论文

> 📄 **A KAN-based Transformer learning network for building energy consumption prediction**
> *Zikuan Qi* — University of Sydney, International Conference (2025)
> 👉 官方代码复现：[KAN-Transformer-BECP](https://github.com/zikuanqi/Enhancing-Building-Energy-Prediction-via-KAN-Transformer-A-Multi-scale-Temporal-Learning-Approach)

---

## 📊 GitHub Stats · 数据统计

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=zikuanqi&show_icons=true&count_private=true&hide_border=true&rank_icon=default&theme=tokyonight" alt="GitHub Stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=zikuanqi&layout=compact&hide_border=true&langs_count=8&theme=tokyonight" alt="Top Languages" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=zikuanqi&hide_border=true&theme=tokyonight" alt="GitHub Streak" />

</div>

---

## 🐍 Contribution Snake · 贪吃蛇活跃度

> 我的 GitHub 贡献格子会被贪吃蛇逐格吃掉 —— 每天自动刷新（由 [`.github/workflows/snake.yml`](.github/workflows/snake.yml) 生成并推送到 `output` 分支）。

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/zikuanqi/zikuanqi/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/zikuanqi/zikuanqi/output/github-contribution-grid-snake.svg" />
  <img alt="snake eating my github contribution graph · 贪吃蛇吃掉我的贡献格子" src="https://raw.githubusercontent.com/zikuanqi/zikuanqi/output/github-contribution-grid-snake.svg" />
</picture>

</div>

---

## 📫 Reach Me · 联系我

- 📧 **Email** · 邮箱：[ziqi5454@uni.sydney.edu.au](mailto:ziqi5454@uni.sydney.edu.au)
- 🏅 **Kaggle**：[Zikuan Qi](https://www.kaggle.com/zikuanqi)
- 🐙 **GitHub**：[github.com/zikuanqi](https://github.com/zikuanqi)

<div align="center">

<sub>⭐️ 如果我的项目对你有帮助，欢迎给个 Star · Thanks for stopping by! ⭐️</sub>

</div>
