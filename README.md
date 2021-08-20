# Code
“悟道”项目提出一系列创新的研究成果，本仓库提供包括模型、算法、工具等在内所有开源成果的源代码链接。

### Model
* **[GLM](https://github.com/BAAI-WuDao/GLM)**

  GLM (General Language Model) 是一个全新的预训练框架，打破BERT和GPT的瓶颈。单一GLM模型在语言理解和生成任务方面取得了最佳结果，并且超过了对相同数据量进行训练的常见预训练模型（例如BERT，RoBERTa和T5）。

* **[Transformer-XL](https://github.com/BAAI-WuDao/Chinese-Transformer-XL)**
  
  Transformers具有长期学习依赖的潜力，但在语言建模设置中受到固定长度上下文的限制。而Transformer-XL作为一种新神经网络架构可以很好地解决长文本依赖问题。悟道基于Transformer-XL训练并开放29亿的语言模型，在长文本生成方面具有优势。

* **[CPM](https://github.com/BAAI-WuDao/CPM)**

  2020年11月，CPM系列正式发布，并推出当时参数最大的26亿中文预训练语言模型CPM-1（Chinese Pretrained Models），可支持简单对话、文章生成和语言理解等下游任务。2021年6月，CPM-2（Cost-efficient Pre-trained language Models）在北京智源大会上发布，推出了110亿的中英双语语言模型和对应的1980亿MoE版模型。
  
* **[EVA](https://github.com/BAAI-WuDao/EVA)**

  EVA是一个开放领域的中文对话预训练模型，是目前最大的汉语对话模型，参数量达到28亿，并且在包括不同领域14亿汉语的悟道对话数据集（WDC）上进行预训练。
  
* **[CogView](https://github.com/BAAI-WuDao/CogView)**
  
  世界最大的中文多模态生成模型，参数量为40亿。模型支持文生成图为基础的多领域下游任务，在应用维度上具备通用性，经过微调后可实现国画、油画、水彩画、轮廓画等图像生成。
  
* **[BriVL](https://github.com/BAAI-WuDao/BriVl)**

  BriVL (Bridging Vision and Language Model) 是首个中文通用图文多模态大规模预训练模型。BriVL模型在图文检索任务上有着优异的效果，超过了同期其他常见的多模态预训练模型（例如UNITER、CLIP）。

* **[ProtTeinLM](https://github.com/BAAI-WuDao/ProteinLM)**

  蛋白质序列预训练模型，目前已开源2亿和30亿参数规模的模型，能支持蛋白质二级结构预测、荧光性预测、接触预测、折叠稳定性预测和远缘同源性检测任务。相较于基线模型TAPE（3800万参数），我们的模型在下游任务上表现有所提升，尤其是在蛋白质折叠问题的接触预测问题上，模型较基线模型提高了16%。
  
* **[Lawformer](https://github.com/BAAI-WuDao/LegalPLMs)**

  在数千万的法律文书上训练能够处理法律长文本的预训练语言模型，参数规模为1亿，支持中文法律长文本输入的理解任务。

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


