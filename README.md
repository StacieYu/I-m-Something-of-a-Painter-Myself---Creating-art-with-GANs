# I-m-Something-of-a-Painter-Myself---Creating-art-with-GANs

This project applies a Generative Adversarial Network (CycleGAN) to convert real-world photos into Monet-style paintings using TensorFlow and Keras. It was developed and submitted as part of a Kaggle competition focused on unpaired image-to-image translation.

🧠 Model
The model used is a CycleGAN, trained to perform unpaired translation from photos to Monet-style artwork. Key components:

generator_g: photo → Monet

generator_f: Monet → photo (not used at inference)

Discriminators to guide adversarial learning

Loss functions include cycle-consistency and identity loss

 Pipeline Overview
Load and preprocess TFRecord datasets of Monet and photo images.

Train the CycleGAN for 10 epochs on the Kaggle GPU runtime.

Generate 300 Monet-style images from test photos using the trained generator.




