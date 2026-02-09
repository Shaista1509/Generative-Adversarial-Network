# Generative-Adversarial-Network
This project studies Generative Adversarial Networks (GANs), where a Generator creates samples and a Discriminator distinguishes real from fake data. Through adversarial training, the Generator learns to approximate the true data distribution.
Generative Adversarial Networks (GANs) are powerful generative models, but their training is often unstable and sensitive to design choices. This project explores the practical challenges of training GANs and investigates how different architectural and training decisions influence convergence and output quality.

A sample notebook (script_gan.ipynb) is provided as a starting point and demonstrates GAN training using the CIFAR-10 dataset. Participants may choose to work with alternative datasets such as MNIST or CelebA. Depending on the dataset choice, it may be necessary to download additional data, adjust the data path, and modify data loading and preprocessing steps. Familiarity with the PyTorch DataLoader is recommended.

The project involves completing the GAN implementation by defining the generator and discriminator networks and running the training process. Particular attention is given to understanding how dataset characteristics affect model design and training behavior. Changes required when switching datasets—such as input dimensions, normalization, and model architecture—are examined and discussed.

During experimentation, observations are documented regarding training dynamics, convergence behavior, and the evolution of generated samples over time. The project further explores how variations in parameters, preprocessing steps, architectural choices, and optimization settings lead to different training outcomes.

To support comparative analysis, multiple training runs are conducted using different configurations. The resulting models are evaluated qualitatively by inspecting generated images and comparatively assessing convergence stability and output diversity. Optional reflections may include suggestions for improving the implementation or training procedure based on empirical findings.
