# awesome-continual-learning / awesome-lifelong-learning
A list of papers, blogs, datasets and software in the field of lifelong/continual machine learning

A powerful concept and a stepping stone towards Artificial General Intelligence.

## Contents
- [Papers](#papers)
- [Blogs](#blogs)
- [Datasets](#dataset)
- [Workshops](#workshops)
- [Startups](#startups)
 
  
# Papers
## Theory & Survey papers

- An empirical investigation of catastrophic forgetting in gradient-based neural networks. [[paper]](https://arxiv.org/abs/1312.6211)
> Talks about the problem of forgetting in neural nets and advantage of using dropout
- Catastrophic interference in connectionist networks: The sequential learning problem. [[paper]](https://www.sciencedirect.com/science/article/pii/S0079742108605368)
> One of the earliest papers introducing the concept of forgetting in learning modules
- Continual Lifelong Learning with Neural Networks: A Review [[paper]](https://arxiv.org/abs/1802.07569)
- Making memories last: the synaptic tagging and capture hypothesis. [[paper]](https://www.ncbi.nlm.nih.gov/pubmed/21170072)
- A massively parallel architecture for a self-organizing neural pattern recognition machine [[paper]](http://sites.bu.edu/steveg/files/2016/06/CarGro1987CVGIP.pdf)
> Talks about the tradeoff between stability (ability to preserve past knowledge) and plasticity (able to rapidly learn new stuffs) 
- Lifelong Machine Learning
> A book on this topic [[draft]](https://www.cs.uic.edu/~liub/lifelong-machine-learning-draft.pdf)

## Approaches
-  Overcoming catastrophic forgetting in neural networks. [[paper]](https://arxiv.org/abs/1612.00796) [[Blog]](https://deepmind.com/blog/enabling-continual-learning-in-neural-networks/) [[Unofficial Implementation]](https://github.com/ariseff/overcoming-catastrophic)
> Penalty applied in the learning process to restrict or consolidate those weights (EWC) that were important (by Fisher information matrix) for the older tasks to change much  
- Less-forgetting learning in deep neural networks [[paper]](https://arxiv.org/abs/1607.00122)
> Regularization based technique by discouraging the final hidden layer's neural representation to change much 
- Learning without forgetting [[paper]](https://arxiv.org/pdf/1606.09282) [[Code]](https://github.com/lizhitwo/LearningWithoutForgetting)
> Uses knowledge distillation based regularization by trying to enforce that the predictions of the new data using the old task's neural parameters do not change much while sequentially learning from the new data only 
- Gradient Episodic Memory for continual learning [[paper]](https://arxiv.org/abs/1706.08840) [[Code]](https://github.com/facebookresearch/GradientEpisodicMemory)
> explain.  An efficient version has been recently proposed in this 2019 [[paper]](https://openreview.net/forum?id=Hkf2_sC5FX)
- iCaRL: Incremental Classifier and Representation Learning [[paper]](https://arxiv.org/abs/1611.07725) [[Code]](https://github.com/srebuffi/iCaRL)
- Continual learning with deep generative replay [[paper]](https://arxiv.org/abs/1705.08690)
- Encoder based lifelong learning [[paper]](https://arxiv.org/abs/1704.01920)  [[Code]](https://github.com/rahafaljundi/Encoder-Based-Lifelong-learning)
- Continual Learning Through Synaptic Intelligence [[paper]](https://arxiv.org/abs/1703.04200) [[Code]](https://github.com/ganguli-lab/pathint)
> Similar to EWC but instead of Fisher information, the importance scores of each weight is computer online along the learning trajectory
- Memory Efficient Experience Replay for Streaming Learning [[paper]](https://arxiv.org/pdf/1809.05922.pdf)
> Explores stream clustering approaches to store subsets to be rehearsed later while learning new data or tasks
- Measuring Catastrophic Forgetting in Neural Networks [[paper]](https://arxiv.org/pdf/1708.02072.pdf)
> New metrics proposed to measure a model's ability to retain past knowledge and acquiring new knowledge
- Memory Replay GANs: learning to generate images from new categories without forgetting [[paper]](https://arxiv.org/pdf/1809.02058.pdf) [[code]](https://github.com/WuChenshen/MeRGAN)
> Another GAN based method to conditionally generate and replay previously learnt data in future learning sessions
- Learning to Learn without Forgetting by Maximizing Transfer and Minimizing Interference. **(2019)** [[paper]](https://openreview.net/pdf?id=B1gTShAct7) 
> Tries to combine reservoir sampling based experience replay with optimization based metalearning
- Overcoming Catastrophic Forgetting for Continual Learning via Model Adaptation **(2019)** [[paper]](https://openreview.net/pdf?id=ryGvcoA5YX)
> In addition to a previous data generator, this paper also has a dynamic weights or parameter generator 



# Datasets
- Core50
- Incremental CIFAR
- Permutated MNIST


# Industry/Startups
- Neurala [[Link]](https://www.neurala.com/tech)
- Cogitai [[Link]](https://www.cogitai.com/)
- Deepmind [[Link]](https://deepmind.com/blog/enabling-continual-learning-in-neural-networks/)

# Blogs
- Why Continual Learning is the key towards Machine Intelligence [[Medium]](https://medium.com/continual-ai/why-continuous-learning-is-the-key-towards-machine-intelligence-1851cb57c308)
- Enabling Continual Learning in Neural Networks, [[Deepmind blog]](https://deepmind.com/blog/enabling-continual-learning-in-neural-networks/)

# Workshops
- [[NIPS 2016 Workshop]](https://sites.google.com/site/cldlnips2016/)
- [[NIPS 2018 Workshop]](https://sites.google.com/view/continual2018)
- [[CVPR 2017 Workshop]](https://erodner.github.io/continuouslearningcvpr2017/)
- [[ICML 2017 Workshop]](http://rlabstraction2016.wixsite.com/icml-2017)
- [[IJCAI 2018 workshop]](https://sites.google.com/view/llarla2018/home)
- [[COSYNE 2019]](http://www.cosyne.org/c/index.php?title=Workshops2019_learning)
