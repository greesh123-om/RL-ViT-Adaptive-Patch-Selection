Abstract

Vision Transformers have shown strong performance in image classification but require high computational resources because they process all image patches equally. This project presents a framework that integrates Reinforcement Learning with Vision Transformers to enable adaptive patch selection.

A Double Deep Q-Network agent learns to select the most informative patches during training and inference. This reduces redundant computation while maintaining classification performance. The system is evaluated on CIFAR-10 and Imagenette datasets and demonstrates an improved balance between efficiency and accuracy.

Objectives
Build a compute-efficient Vision Transformer
Learn adaptive patch selection using Reinforcement Learning
Reduce unnecessary attention computation
Maintain or improve classification accuracy
Design a scalable and efficient deep learning pipeline
Methodology

The system combines a Vision Transformer with a Reinforcement Learning agent.

Key Contributions
Integration of Reinforcement Learning with Vision Transformers
Adaptive patch selection using a Double DQN agent
Reduction in computational cost through selective attention
Consistent policy used during both training and evaluation
General framework for efficient transformer-based models
