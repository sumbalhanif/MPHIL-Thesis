Have worked on knowledge distillation, where we aimed to create a simple (student) model from a complex (teacher) model that performs similarly to the teacher model but requires fewer resources and less time while achieving same results. The motivation behind choosing this topic was that we often face resource limitations. By distilling knowledge into a lightweight model, we can enable inference on handheld devices. 

Furthermore, I have worked on two datasets for this: one is a Protein-Protein Interaction (PPI) dataset and the other is the Cora dataset. The PPI dataset is about human tissues, while the Cora dataset is a citation network. Both datasets have different natures, but I successfully applied the same technique on both.

Used Pytorch framework and Have trained a Graph Attention Model, which is a special type of Graph Neural Network.
In the literature, knowledge distillation typically uses only local loss and structure. My contribution was introducing the global loss and incorporating it with the local loss. This not only improved the model’s performance but also reduced the number of training parameters, which in turn automatically reduced the training time.

Additionally, I conducted experiments on both datasets using both hard and soft labels. I observed an improvement in results with hard labels. To the best of my knowledge, I successfully conducted the experiment with hard labels, which is a unique contribution to the literature.
