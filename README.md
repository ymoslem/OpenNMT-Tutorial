# OpenNMT-py Tutorial
Neural Machine Translation (NMT) tutorial with [OpenNMT-py](https://github.com/OpenNMT/OpenNMT-py). Data preprocessing, model training, evaluation, and deployment.

## Fundamentals
* Data Processing ([notebook](1-NMT-Data-Processing.ipynb) | [code](https://github.com/ymoslem/MT-Preparation))
* NMT Model Training with OpenNMT-py ([notebook](2-NMT-Training.ipynb))
* Translation/Inference with CTranslate2 ([code](https://gist.github.com/ymoslem/60e1d1dc44fe006f67e130b6ad703c4b))
* MT Evaluation with BLEU and other metrics ([tutorial](https://blog.machinetranslation.io/compute-bleu-score/) | [code](https://github.com/ymoslem/MT-Evaluation) | [notebook](https://github.com/ymoslem/Adaptive-MT-LLM/blob/main/evaluation/Evaluation.ipynb))
* Simple Web UI ([tutorial](https://blog.machinetranslation.io/nmt-web-interface/) | [code](https://github.com/ymoslem/OpenNMT-Web-Interface))

## Advanced Topics
* Running TensorBoard with OpenNMT ([tutorial](https://blog.machinetranslation.io/TensorBoard/))
* Low-Resource Neural Machine Translation ([tutorial](https://blog.machinetranslation.io/low-resource-nmt/))
* Domain Adaptation with Mixed Fine-tuning ([tutorial](https://blog.machinetranslation.io/domain-adaptation-mixed-fine-tuning/))
* Overview of Domain Adaptation Techniques ([tutorial](https://amtaweb.org/wp-content/uploads/2020/11/NMTDomainAdaptationTechniques.pdf))
* Multilingual Machine Translation ([tutorial](https://blog.machinetranslation.io/multilingual-nmt/))
* Using Pre-trained NMT models with CTranslate2 ([M2M-100](https://gist.github.com/ymoslem/a414a0ead0d3e50f4d7ff7110b1d1c0d) | [NLLB-200](https://github.com/ymoslem/Adaptive-MT-LLM/blob/main/MT/NLLB.ipynb))
* Domain-Specific Text Generation for Machine Translation ([paper](https://aclanthology.org/2022.amta-research.2/) | [article](https://blog.machinetranslation.io/synthetic-data-machine-translation/) | [code](https://github.com/ymoslem/MT-LM))
* Adaptive Machine Translation with Large Language Models ([paper](https://aclanthology.org/2023.eamt-1.22/) | [code](https://github.com/ymoslem/Adaptive-MT-LLM))
* Fine-tuning Large Language Models for Adaptive Machine Translation ([paper](https://arxiv.org/abs/2312.12740) | [code](https://github.com/ymoslem/Adaptive-MT-LLM-Fine-tuning))

## Citations

```bibtex
@misc{moslem-2022-OpenNMTtutorial,
    title = "{OpenNMT-py} Tutorial: Neural Machine Translation Data Preprocessing, Model Training, and Evaluation",
    author = "Moslem, Yasmin",
    year = "2022",
    publisher = "GitHub",
    url = "https://github.com/ymoslem/OpenNMT-Tutorial",
    note = "GitHub repository"
}
```

```bibtex
@inproceedings{moslem-etal-2022-domain,
    title = "Domain-Specific Text Generation for Machine Translation",
    author = "Moslem, Yasmin  and
      Haque, Rejwanul  and
      Kelleher, John  and
      Way, Andy",
    booktitle = "Proceedings of the 15th biennial conference of the Association for Machine Translation in the Americas (Volume 1: Research Track)",
    month = sep,
    year = "2022",
    address = "Orlando, USA",
    publisher = "Association for Machine Translation in the Americas",
    url = "https://aclanthology.org/2022.amta-research.2",
    pages = "14--30",
}
```

```bibtex
@inproceedings{klein-etal-2020-efficient,
    title = "Efficient and High-Quality Neural Machine Translation with {O}pen{NMT}",
    author = "Klein, Guillaume  and
      Zhang, Dakun  and
      Chouteau, Cl{\'e}ment  and
      Crego, Josep  and
      Senellart, Jean",
    booktitle = "Proceedings of the Fourth Workshop on Neural Generation and Translation",
    month = jul,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2020.ngt-1.25/",
    doi = "10.18653/v1/2020.ngt-1.25",
    pages = "211--217",
}
```
