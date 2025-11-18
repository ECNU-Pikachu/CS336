# CS336 课程作业

本仓库包含自用的 CS336 课程的作业代码

## 📁 项目结构

```
cs336-assignments/
├── assignment1-basics/     # Transformer 基础实现
├── assignment2-pretraining/ # 预训练与微调
├── assignment3-rlhf/       # 基于人类反馈的强化学习
└── README.md
```

## 🚀 快速开始

### 环境要求
- Python 3.8+
- PyTorch 2.0+
- CUDA（可选，用于GPU加速）

### 安装步骤
```bash
# 克隆仓库
git clone https://github.com/your-username/cs336-assignments.git
cd cs336-assignments

# 创建虚拟环境
python -m venv cs336_env
source cs336_env/bin/activate  # Linux/Mac
# 或
cs336_env\Scripts\activate    # Windows

# 安装依赖
pip install -r requirements.txt
```

### 运行作业
```bash
# 作业1：Transformer基础
cd assignment1-basics
pytest tests/ -v

# 作业2：预训练
cd assignment2-pretraining
python train.py

# 作业3：RLHF
cd assignment3-rlhf
python rlhf_training.py
```

## 📚 作业内容

### 作业1：Transformer基础
- 实现多头自注意力机制
- 实现RoPE位置编码
- 构建完整的Transformer块
- 实现语言模型前向传播

### 作业2：预训练与微调



## 📊 结果展示

各作业的详细实验结果和性能指标请参考各作业目录下的`results/`文件夹。

## 🤝 贡献

欢迎提交Issue和Pull Request来改进代码或修复问题。

## 📄 许可证

本项目仅用于学习目的，遵循MIT许可证。

---

*注：本仓库为课程作业实现，仅供学习参考。*
```
