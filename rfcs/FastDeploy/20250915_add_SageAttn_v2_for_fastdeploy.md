# 为FastDeploy集成 SageAttn v2/2++设计文档

| 任务名称                                                       | 为FastDeploy集成 SageAttn v2/2++                                  | 
|----------------------------------------------------------|-------------------------------------------|
| 提交作者   | WanRui37  | 
| 提交时间   | 2025-09-15 | 
| 版本号  | V1.0 | 
| 依赖飞桨版本 | FastDeploy develop   | 
| 文件名  | 20250915_add_SageAttn_v2_for_fastdeploy.md<br> |


# 一、概述
## 1、相关背景
SageAttn v2/2++ 是清华团队为进一步加速 SageAttn 所提方案。FastDeploy框架需要更完善的xxx

## 2、功能目标
- 为FastDeploy 集成SageAttn v2/2++ 高性能量化 Attention能力；
- 将上述算子集成到EB、DeepSeek、Qwen等模型中，使得端到端性能有所提升。

## 3、意义
完善 FastDeploy 对大模型低精度高性能 Attention 的支持，助力 FastDeploy 实现高效部署全场景大模型的产品目标。


# 二、设计思路与实现方案


# 三、测试和验收的考量


# 四、可行性分析和排期规划
- 2025-9-15 ~ 2025-9-31：完成集成代码开发
- 2025-9-31 ~ 2025-10-10：完成代码测试
- 2025-10-10 ~ 2025-10-16： 完成部署示例及文档

# 五、影响面


# 六、参考资料
1. [SageAttention 官方github仓库](https://github.com/thu-ml/SageAttention)

1. [SageAttention v2 论文](https://arxiv.org/abs/2411.10958)

