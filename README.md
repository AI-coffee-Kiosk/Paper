---------
# Evaluating LLaMA Model for Enhanced Conversational AI in Voice Recognition Kiosks: A Case Study on RASA vs LLaMA.

## 📄 Research Paper Overview

This repository contains the research paper titled **"Evaluating LLaMA Model for Enhanced Conversational AI in Voice Recognition Kiosks: A Case Study on RASA vs LLaMA."** The study explores the effectiveness of the LLaMA language model as an alternative to the RASA framework for implementing conversational AI in voice recognition kiosks, specifically in retail environments like cafes. The research compares the performance of both models, highlighting improvements in handling complex interactions and enhancing user experience.

## 📝 Abstract

The paper evaluates the LLaMA model's capabilities in handling diverse user commands and complex order modifications compared to the traditional RASA framework. The study demonstrates LLaMA’s superior performance in terms of accuracy, flexibility, and scalability, making it a robust solution for customer-facing applications. Key findings indicate that LLaMA significantly enhances user interaction and reduces errors in real-world scenarios.

## 📚 Table of Contents

- [Introduction](#introduction)
- [System Architecture](#system-architecture)
- [Dataset and Training](#dataset-and-training)
- [Comparative Analysis](#comparative-analysis)
- [Results and Discussion](#results-and-discussion)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [References](#references)

## 🚀 Introduction

Conversational AI in kiosks, such as those used for cafe ordering, is transforming customer interactions by providing hands-free and efficient ordering processes. Traditional models like RASA, although effective in intent classification, often struggle with understanding complex commands. This study introduces the LLaMA model as a more advanced alternative, capable of handling nuanced language comprehension and improving the overall user experience.

## 🛠️ System Architecture

The kiosk system integrates:
- **LLaMA Language Model**: For natural language understanding and response generation.
- **Google Cloud APIs**: Used for Speech-to-Text (STT) and Text-to-Speech (TTS) functionalities.
- **User Interface**: Built with PYQT for a seamless interaction experience.

The architecture focuses on real-time processing, ensuring quick and accurate responses to user commands. A comprehensive diagram of the system design is provided in the research paper.

## 📊 Dataset and Training

- **Dataset Creation**: The dataset includes 4,500 unique dialogue scenarios, covering a wide range of order types from simple to complex modifications.
- **Data Processing**: Structured inputs with emphasis on key order features (e.g., drink type, size, preferences) were used to create realistic dialogues.
- **Model Training**: Fine-tuning was performed using the **Unsloth framework** on Google Colab, utilizing Python and Hugging Face tools. The model was optimized in a 4-bit quantized format to enhance speed and reduce memory usage.

## 🔍 Comparative Analysis

### RASA vs. LLaMA

The comparative study focused on:
- **Flexibility**: LLaMA showed robust adaptability in understanding varied user commands, outperforming RASA in handling unexpected phrasing and complex inputs.
- **Accuracy**: LLaMA demonstrated higher success rates in complex order scenarios, while RASA struggled with precision and recall.
- **User Experience**: Enhanced performance of LLaMA led to fewer errors and smoother interactions.

## 📈 Results and Discussion

Key performance metrics analyzed include:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

The results show that LLaMA consistently outperformed RASA across all metrics, especially in handling complex and ambiguous commands. Detailed tables and graphs illustrating the performance comparison are available in the paper.

## 🏆 Conclusion

The study concludes that:
- While RASA is effective for structured and straightforward interactions, it is limited in dynamic, real-world scenarios.
- LLaMA’s advanced language modeling capabilities make it a superior choice for voice-based conversational AI applications, particularly in high-demand retail settings.

## 🔮 Future Work

- Further optimization of LLaMA’s response time through additional model compression techniques.
- Real-world testing and user feedback collection to refine the model’s training and improve its adaptability.

## 📚 References

1. Bocklisch, Tom, et al. "Rasa: Open source language understanding and dialogue management." arXiv preprint arXiv:1712.05181 (2017).
2. Touvron, Hugo, et al. "Llama 2: Open foundation and fine-tuned chat models."

## 💬 Contact

For any questions or further discussions about this research, please feel free to reach out.

-------
