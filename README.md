## Projects:
1. [shakespeare-gpt](https://github.com/garipovroma/shakespeare-gpt) 
   * The GPT-2 model fine-tuned on Shakespeare plays dataset to generate text in Shakespeare style
   * Fine-tuning pipeline implemented both using pure PyTorch and transformers Trainer
   * The [Nucleus sampling](https://arxiv.org/abs/1904.09751) text generation strategy implemented
2. [DeepTable - bachelor thesis](https://github.com/garipovroma/bachelor-thesis)
    * A grade bachelor thesis
   * Learned approaches in Meta Learning on tabular from simple classical methods to neural networks architectures
   * Proposed DNN architecture called DeepTable which uses the idea of [Deep Sets](https://papers.nips.cc/paper_files/paper/2017/hash/f22e4747da1aa27e363d86d40ff442fe-Abstract.html)
   * The developed architecture implemented using PyTorch, accuracy of trained model is 5% higher than that of [LM-GAN](https://dl.acm.org/doi/10.1145/3369114.3369153) and 32% higher than that of classical meta learning algorithms while the number of parameters is 100 times fewer than LM-GAN
3. [conveyor-detection](https://github.com/garipovroma/conveyor-detection)
    * Collected and labeled a dataset of 500 images for the semantic line segmentation problem
   * Realized a basic approach using OpenCV algorithms such as Hough Line Transform for line detection
   * An approach with the ResNet DNN as backbone implemented on PyTorch for the semantic line segmentation problem
   * Proposed an application of the Deep Hough Transform approach described in the [Deep Hough Transform for Semantic Line Detection(ECCV 2020)](https://arxiv.org/abs/2003.04676v4) which improved accuracy up to 75% and f-score up to 64%

