# Classic architecture

## Survey
- **Foundation Models for Decision Making: Problems, Methods, and Opportunities**[link](https://arxiv.org/abs/2303.04129)
## Decison Transformer
- **Decision Transformer: Reinforcement Learning via Sequence Modeling**[link](https://proceedings.neurips.cc/paper/2021/hash/7f489f642a0ddb10272b5c31057f0663-Abstract.html)

## Decision Convformer
- **Decision ConvFormer: Local Filtering in MetaFormer is Sufficient for Decision Making** [link](https://arxiv.org/abs/2310.03022)
  - 质疑了DT中attention提取全局token关系不符合马尔可夫的遗忘性质，提出将metaformer中的token mixer换成Convolution block，提高离线RL预测效果同时降低了参数量
  - ![image](https://github.com/user-attachments/assets/6730e93f-79f1-42ff-9db1-70e0ce96070d)

## Decision Mamba
- **Mamba: Linear-time sequence modeling with selective state spaces** [link](https://arxiv.org/abs/2312.00752
- **Decision Mamba: Reinforcement Learning via Sequence Modeling with Selective State Spaces** [link](https://arxiv.org/abs/2403.19925)
  - 首次尝试将metaformer中的token mixer替换为mamba block，验证了DM在offline RL问题中的决策可行性，但效果不如的类似架构的decision Convformer
- **Is Mamba Compatible with Trajectory Optimization in Offline Reinforcement Learning?** [link](https://arxiv.org/abs/2405.12094)

