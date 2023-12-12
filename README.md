# Comparing-Image-to-Text-Models-BLIP-BLIP2-and-LLaVA

![alt text][def]

[def]: reference_image.jpeg

## 1. BLIP: Bootstrapping Language-Image Pre-training for Unified Vision-Language Understanding and Generation
### Overview
Vision-Language Pre-training (VLP) is the approach that involves training models on joint visual and textual data. In this paper, authors introduce a new VLP framework called BLIP (Bootstrapping Language-Image Pairs) . The term "bootstrapping" implies a self-improvement process, where the model makes effective use of the large scale noisy web image-text data by iteratively improving or refining the captions. 
The model achieves state-of-the-art results on various vision-language tasks like image-text retrieval, image captioning, visual question answering, visual reasoning, visual dialog and generalization ability when directly transferred to video-language tasks in a zero-shot manner.



## 2. BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models
#### Overview
The paper presents a new pre-training strategy called BLIP-2 for vision-language tasks. BLIP-2 is a compute-efficient method that uses off-the-shelf pre-trained vision models and large language models (LLMs) to bootstrap vision-language representation learning and generative learning. The pre-training is done in two stages, and the resulting Querying Transformer achieves state-of-the-art performance on several benchmarks while using significantly fewer trainable parameters than previous methods. The Querying Transformer bridges the modality gap between vision and language.
BLIP-2 also enables zero-shot instructed image-to-text generation, which allows for a wide range of capabilities including visual knowledge reasoning, visual common sense reasoning, visual conversation, and personalized image-to-text generation.

## 3. LLaVA: Large Language and Vision Assistant
#### Overview
This research introduces LLaVA (Large Language and Vision Assistant), a large multimodal model that connects a vision encoder with a language model, aiming for general purpose visual and language understanding. 
The model is trained end-to-end using instruction-tuning with language-only GPT-4 generated multimodal instruction-following data. LLaVA exhibits impressive multimodal chat abilities and achieves a significant relative score compared to GPT-4 on a synthetic multimodal instruction-following dataset.
