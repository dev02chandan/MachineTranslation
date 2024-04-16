# Multilingual Translation System
<img width="324" alt="Screenshot 2024-04-16 at 5 34 48 PM" src="https://github.com/dev02chandan/MachineTranslation/assets/73015720/529a7cd7-27b7-43e1-ac19-c6ef419c6a59">

This repository contains a multilingual translation system powered by the Helsinki-NLP/opus-mt model from Hugging Face. The system is designed to handle translations between English and five other languages, both ways. This README outlines the project setup, usage instructions, and additional details about our custom finetuning.

## Model Description

This translation system utilizes the Helsinki-NLP/opus-mt models, which are pre-trained models for machine translation based on the Marian framework. These models were chosen for their efficiency in translating between multiple languages. The models have been further fine-tuned with specific translations to tailor the output more closely to project requirements.

## Languages Supported

The system supports translation between English and the following languages:

- Dutch
- French
- Spanish
- Arabic
- German

## Finetuning

The Helsinki-NLP/opus-mt model was fine-tuned to better reflect specific translation preferences and terminology relevant to our use case. This custom finetuning involved adjusting the translations to fit particular phrasing and nuances that were critical for our application.

## Getting Started

Use the Notebooks directly for translation and finetuning.

## Contributing

Contributions to this project are welcome. 

## Acknowledgments

- Helsinki-NLP for providing the opus-mt models.
- Hugging Face for hosting the model on their platform.
