# ChineseMenuCSI

This repository hosts the **ChineseMenuCSI** dataset, introduced in the paper [**"Cultural Adaptation of Menus: A Fine-Grained Approach"**](https://aclanthology.org/2024.wmt-1.120), presented at the **WMT (Conference on Machine Translation)** at EMNLP 2024.

The **ChineseMenuCSI** dataset is specifically designed for research in cultural adaptation, with a focus on fine-grained translation and analysis of culinary terms in Chinese menus across diverse cultural contexts.

We plan to release the code for the menu parser associated with this dataset in the near future. Stay tuned for updates!

---

## Authors

- Zhonghe Zhang  
- Xiaoyu He  
- Vivek Iyer  
- Alexandra Birch  

---

## How to Cite

If you use the **ChineseMenuCSI** dataset or find our work helpful, please cite the following:

```bibtex
@inproceedings{zhang-etal-2024-cultural,
    title = "Cultural Adaptation of Menus: A Fine-Grained Approach",
    author = "Zhang, Zhonghe  and
      He, Xiaoyu  and
      Iyer, Vivek  and
      Birch, Alexandra",
    editor = "Haddow, Barry  and
      Kocmi, Tom  and
      Koehn, Philipp  and
      Monz, Christof",
    booktitle = "Proceedings of the Ninth Conference on Machine Translation",
    month = nov,
    year = "2024",
    address = "Miami, Florida, USA",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.wmt-1.120",
    pages = "1258--1271",
    abstract = "Machine Translation of Culture-Specific Items (CSIs) poses significant challenges. Recent work on CSI translation has shown some success using Large Language Models (LLMs) to adapt to different languages and cultures; however, a deeper analysis is needed to examine the benefits and pitfalls of each method. In this paper, we introduce the ChineseMenuCSI dataset, the largest for Chinese-English menu corpora, annotated with CSI vs Non-CSI labels and a fine-grained test set. We define three levels of CSI figurativeness for a more nuanced analysis and develop a novel methodology for automatic CSI identification, which outperforms GPT-based prompts in most categories. Importantly, we are the first to integrate human translation theories into LLM-driven translation processes, significantly improving translation accuracy, with COMET scores increasing by up to 7 points. The code and dataset are available at https://github.com/Henry8772/ChineseMenuCSI.",
}
