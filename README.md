# cycleGANs
Cycle-GAN with Self Attention

CycleGAN is a type of Generative Adversarial Network (GAN) that enables image-to-image translation in an unsupervised manner. This means it can convert images from one domain to another without needing paired examples. Common applications include style transfer, season transfer, and photo enhancement.



Why Add Self-Attention to CycleGAN?

Self-attention mechanisms allow the network to weigh the importance of different regions in the input data, regardless of their position. In the context of image translation:

Detail Preservation: Attention can help preserve details by focusing on relevant features, which is especially beneficial in complex translations like changing facial expressions, altering seasons in landscapes, or converting paintings to photographs. Global Context: It integrates global contextual information better than convolutions alone, which primarily capture local features.
