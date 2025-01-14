# Music Composition with Generative Models
Leveraged Generative Adversarial Networks (GANs) to generate jazz music compositions, achieving 92% accuracy in the process.

## Introduction
- This project explores AI-driven music generation using a hybrid GAN framework combining four types of generators: Fully Connected, LSTM, Transformer, and Variational Autoencoder (VAE). 
- Imposing a refined MIDI dataset and advanced preprocessing techniques, it aims to produce diverse and meaningful jazz music samples. 
- By integrating GAN's adversarial training with hyperparameter tuning, the framework generates harmonious and aesthetically pleasing compositions, pushing the boundaries of generative music creation to inspire musicians and composers.

## Methodology 
<div align="center">
    <img src="WhatsApp Image 2025-01-14 at 16.11.43_0a481cb2.jpg" alt="Alt text" />
</div>


- Features four generators (Fully Connected, LSTM, Transformer, and VAE) and a discriminator for adversarial training to distinguish real from generated   sequences under a GAN framework.
- Each generator specializes in capturing different musical aspects, producing coherent sequences from random noise input.
- Generators and discriminator iteratively refine outputs through adversarial feedback, leveraging batch normalization and activation functions for stability.
- Generated sequences are scaled, converted to MIDI, and analyzed for uniqueness and quality using MIDI metadata extraction.

## Results
- After hyperparameter tuning, accuracy improved to 92% with optimized settings: sequence length = 30, latent dimension = 17, batch size = 50, learning rate = 0.001, and epochs = 15. 
- These adjustments reduced overfitting, computational complexity, and instability while enhancing output diversity and quality.

## Future Scope 
- Expand the model to blend multiple music genres, enabling innovative and hybrid compositions.
- Enhance the model to generate music in real-time for live performances or interactive applications, such as AI music accompanists or gaming soundtracks.
- Help Music artists out of the pressure to create unique and catchy beats every single time

## Acknowledgement
This project incorporates knowledge and resources from various open-source contributions, research works, and tools. All sources, whether directly cited or indirectly referenced, have played a role in shaping this work.
