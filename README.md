# Code
“悟道”项目提出一系列创新的研究成果，本仓库提供包括模型、算法、工具等在内所有开源成果的源代码链接。

### Model
* **[GLM](https://github.com/THUDM/GLM)**

  GLM是英文通用（多任务）大规模预训练模型，参数规模达到100亿。

* **[CogView](https://github.com/THUDM/CogView)**
  
  CogView是世界最大的中文多模态生成模型，参数量达到40亿。

* **[CPM](https://github.com/TsinghuaAI/CPM)**

  兼顾理解与生成能力的预训练语言模型系列，涵盖中文、中英双语多类模型，目前已开源26亿CPM-1、110亿和1980亿参数CPM-2模型。

* **[ProtTrans](https://github.com/THUDM/ProteinLM)**

  国内最大的蛋白质预训练模型，参数总量达到30亿。
  
* **[Lawformer](https://github.com/thunlp/LegalPLMs)**

  世界首创法律领域长文本中文预训练模型，参数规模达到1亿。

### Algorithm
* **[P-tuning](https://github.com/TsinghuaAI/CPM-1-Finetune)**
 
  新型的微调范式，历史上首次实现自回归模型在理解任务上超越自编码模型，并在知识探测和小样本学习的多个数据集上取得世界第一，提升高达20百分点。

* **[Inverse Prompting](https://github.com/THUDM/InversePrompting)**
  
  新型的文本生成算法，显著改善了对语言模型生成结果的控制，在问答和诗歌生成任务中接近人类水平。

### Tool
* **[FastMoE](https://github.com/laekov/fastmoe)**
  
  高性能的MoE系统，万亿模型的核心技术，首个支持PyTorch框架的高性能MoE系统，相比PyTorch朴素实现速度提升47倍。

* **[InfMoE](https://github.com/Harry-Chen/InfMoE)**

  采用TensorRT实现框架，世界首创低资源大模型推理系统，单卡GPU可以进行千亿规模模型的推理。
  
* **[预训练知识继承](https://github.com/thunlp/Knowledge-Inheritance)**

  世界首创大规模预训练融合框架-缩短大模型近50%前期训练时间

* **[3D加速框架TDS](https://github.com/TsinghuaAI/TDS)**

  世界首创大规模预训练融合框架，能够缩短大模型近50%前期训练时间。
  
* **[ProteinLM](https://github.com/THUDM/ProteinLM)**

  将蛋白质语言模型移植到Megatron-LM框架下进行训练，更好的支持多机集群训练、模型并行和数据并行。
