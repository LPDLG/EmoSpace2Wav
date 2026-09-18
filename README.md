# EmoSpace2Wav
## Project Profile
This repository is used for presentations on the EmoSpace2Wav framework and the EmoACLP dataset. Here, we provide representative landscape paintings, generated audio samples, and corresponding emotion information.

# EmoSpace2Wav
Generating audio from traditional Chinese landscape paintings is a challenging cross-modal task. Existing image-to-audio methods mainly focus on explicit visual semantics, while the implicit aesthetic emotions contained in highly stylized artworks are less directly represented. This may limit the correspondence between visual content, aesthetic emotion, and generated acoustic patterns.

To address this problem, we propose EmoSpace2Wav, an emotion-aware audio generation framework for traditional Chinese landscape paintings. The framework combines CLIP-based visual semantics with fine-grained aesthetic-emotion features through Multi-View Embedding Alignment to construct an explicit Object--Emotion representation. A Transformer-based Progressive Prior equipped with Lite-KAN further models acoustic representations through a coarse-to-refined generation process.

We also construct EmoACLP, a synthetic teacher-generated multimodal dataset containing 7,048 Chinese landscape paintings with image, audio, text, and six-category aesthetic-emotion information. The dataset provides multimodal supervision for studying emotion-aware cross-modal audio generation.

Experimental results show that EmoSpace2Wav achieves strong performance in acoustic quality, cross-modal semantic alignment, and discrete emotion recognition. Human evaluations and real traditional-audio experiments further demonstrate the effectiveness of integrating visual semantics with aesthetic-emotion information.

# code
We will upload the training code, test code, audio samples, and dataset information at an appropriate time!
