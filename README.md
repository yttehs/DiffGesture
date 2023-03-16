# Taming Diffusion Models for Audio-Driven Co-Speech Gesture Generation (CVPR 2023)

We will update README soon.

## Abstract

Animating virtual avatars to make co-speech gestures facilitates various applications in human-machine interaction. The existing methods mainly rely on generative adversarial networks (GANs), which typically suffer from notorious mode collapse and unstable training, thus making it difficult to learn accurate audio-gesture joint distributions. In this work, we propose a novel diffusion-based framework, named **Diffusion Co-Speech Gesture (DiffGesture)**, to effectively capture the cross-modal audio-to-gesture associations and preserve temporal coherence for high-fidelity audio-driven co-speech gesture generation. Specifically, we first establish the diffusion-conditional generation process on clips of skeleton sequences and audio to enable the whole framework. Then, a novel Diffusion Audio-Gesture Transformer is devised to better attend to the information from multiple modalities and model the long-term temporal dependency. Moreover, to eliminate temporal inconsistency, we propose an effective Diffusion Gesture Stabilizer with an annealed noise sampling strategy. Benefiting from the architectural advantages of diffusion models, we further incorporate implicit classifier-free guidance to trade off between diversity and gesture quality. Extensive experiments demonstrate that DiffGesture achieves state-of-the-art performance, which renders coherent gestures with better mode coverage and stronger audio correlations.

## Related Links
If you are interested in **Audio-Driven Co-Speech Gesture Generation**, we would also like to recommend you to check out our other related works:

* Hierarchical Audio-to-Gesture, [HA2G](https://alvinliu0.github.io/projects/HA2G).

* Audio-Driven Co-Speech Gesture Video Generation, [ANGIE](https://alvinliu0.github.io/projects/ANGIE).
