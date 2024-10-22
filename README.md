
## Introduction : 

This notebook presents a series of examples using Hugging Face  models to accomplish various tasks in the fields of NLP, computer vision, and audio. The goal is to demonstrate the versatile capabilities of pretrained models and show how they can be applied.

## Objectives of the Notebook:

- Explore the capabilities of Hugging Face pretrained models across different domains.
  
- Learn how to load and use these models for specific tasks.
  
- Understand how Hugging Face pipelines simplify the inference process.
  
- Demonstrate interoperability between different modalities (text, audio, image).

## Tasks Covered : 

**1 - Text2Text** (Text completion, Text Generation, summarization): Using models ( facebook/blenderbot-400M-distill ) to translate texts, summarize , and generate text from specific prompts.

**2 - Speech2Text:** Implementing models (facebook/nllb-200-distilled-600M & facebook/bart-large-cnn) to transcribe audio into text, enabling the conversion of speech into written text.

**3 - Sentence embedding:** to generate meaningful vector (all-MiniLM-L6-v2) representations of sentences for tasks like semantic similarity, clustering, and information retrieval.

**4 - Audio Classification:** Using model (laion/clap-htsat-unfused) to classify audio clips based on their content, for example, recognizing environmental sounds or emotions in voice.

**5 - Speech to text:** Applying TTS models (distil-whisper/distil-small.en) to transform text into synthesized speech, illustrating how machines can vocalize textual content.

**6 - Text to Speech:** Applying TTS models ( Bark model, Speecht5_tts) to transform text into synthesized speech, illustrating how machines can give voice to text.

**7 - Object Detection:** Employing models like (facebook/detr-resnet-50) to detect and locate objects within images, with potential applications in surveillance, robotics, and more.

**8 -  Image Captioning** with Multimodels: Implementing models such as BLIP (Bootstrapping Language-Image Pre-training) to generate descriptive captions for images, bridging the gap between visual content and natural language understanding 

**9 - Visual Question Answering on Images:** Combining vision and language model (Salesforce/blip-vqa-base)  to answer questions about the content of an image, demonstrating the integration between visual and linguistic understanding.
