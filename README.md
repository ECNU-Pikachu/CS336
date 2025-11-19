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

### 环境配置
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

# 作业2：

```

## 📚 作业内容

### 作业1：Building a Transformer LM
- pytest tests/test_train_bpe.py 测试点通过（2/3），测试点1可通过建立反向索引/使用更好的处理器尝试解决
- pytest tests/test_tokenizer.py 测试点未通过，本作业本应在Linux环境实现，但是我在Windows下实现，因此缺少resource库，在Linux写作业的小伙伴可以尝试运行pytest，若在Windows下运行，注意将'/tests'下的'test_tokenizer.py'改名，使pytest无法正确识别以顺利进行其他测试，例如改为'test_tokenizer.py.bak'
- pytest -k test_linear 测试点通过
- pytest -k test_embedding 测试点通过
- pytest -k test_rmsnorm 测试点通过
- pytest -k test_swiglu 测试点通过
- pytest -k test_rope 测试点通过
- pytest -k test_softmax_matches_pytorch 测试点通过
- pytest -k test_scaled_dot_product_attention 测试点通过
- pytest -k test_4d_scaled_dot_product_attention 测试点通过
- pytest -k test_multihead_self_attention 测试点通过（2/2）
- pytest -k test_transformer_block 测试点通过
- pytest -k test_transformer_lm 测试点通过（2/2）

### 作业2：预训练与微调



## 📊 结果展示

各作业的详细实验结果和性能指标请参考各作业目录下的`results/`文件夹。

## 🤝 贡献

欢迎提交Issue和Pull Request来改进代码或修复问题。

## 📄 许可证

本项目采用 MIT 许可证 - 详情请见 `LICENSE` 文件。

---

*注：本仓库为课程作业实现，仅供学习参考。*
```
