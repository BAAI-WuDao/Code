# Code
“悟道”项目提出一系列创新的研究成果，本仓库提供包括模型、算法、工具等在内所有开源成果的源代码链接。

### Model
* **[GLM](https://github.com/BAAI-WuDao/GLM)**

  以英文为核心的预训练语言模型系列，基于新的预训练范式实现单一模型在语言理解和生成任务方面取得了最佳结果，并且超过了在相同数据量进行训练的常见预训练模型（例如BERT，RoBERTa和T5），目前已开源1.1亿、3.35亿、4.10亿、5.15亿、100亿参数规模的模型。

* **[Transformer-XL](https://github.com/BAAI-WuDao/Chinese-Transformer-XL)**
  
  基于Transformer-XL训练的以中文为核心的预训练语言生成模型，参数规模为29亿，目前可支持包括文章生成、智能作诗、评论/摘要生成等主流NLG任务。

* **[CPM](https://github.com/BAAI-WuDao/CPM)**

  兼顾理解与生成能力的预训练语言模型系列，涵盖中文、中英双语多类模型，目前已开源26亿、110亿和1980亿参数规模的模型。
  
* **[CogView](https://github.com/BAAI-WuDao/CogView)**
  
  参数量为40亿，模型可实现文本生成图像，经过微调后可实现国画、油画、水彩画、轮廓画等图像生成。目前在公认MS COCO文生图任务上取得了超过OpenAI DALL·E的成绩，获得世界第一。
  
* **[BriVL](https://github.com/BAAI-WuDao/BriVl)**

  BriVL (Bridging Vision and Language Model) 是首个中文通用图文多模态大规模预训练模型，参数量达10亿。BriVL模型在图文检索任务上有着优异的效果，超过了同期其他常见的多模态预训练模型（例如UNITER、CLIP）。

* **[ProtTrans](https://github.com/BAAI-WuDao/ProteinLM)**

  国内最大的蛋白质预训练模型，参数总量达到30亿。
  
* **[Lawformer](https://github.com/BAAI-WuDao/LegalPLMs)**

  世界首创法律领域长文本中文预训练模型，参数规模达到1亿。

### Algorithm
* **[P-tuning](https://github.com/BAAI-WuDao/P-tuning)**
 
  新型的微调范式，历史上首次实现自回归模型在理解任务上超越自编码模型，并在知识探测和小样本学习的多个数据集上取得世界第一，提升高达20百分点。

* **[Inverse Prompting](https://github.com/BAAI-WuDao/iPrompt)**
  
  新型的文本生成算法，显著改善了对语言模型生成结果的控制，在问答和诗歌生成任务中接近人类水平。

### Tool
* **[FastMoE](https://github.com/BAAI-WuDao/fastmoe)**
  
  首个支持国产超算和GPU的高性能MoE系统，支持Switch，Gshard等复杂均衡策略。

* **[InfMoE](https://github.com/BAAI-WuDao/InfMoE)**

  世界首创低资源大模型推理系统，单卡GPU可以进行千亿规模模型的推理。
  
* **[预训练知识继承](https://github.com/BAAI-WuDao/Knowledge-Inheritance)**

  世界首创大规模预训练融合框架-缩短大模型近50%前期训练时间

* **[3D加速框架TDS](https://github.com/BAAI-WuDao/TDS)**

  DeepSpeed结合TDS插件，可同时支持数据/模型/流水并行、ZeRO和混合加速。


