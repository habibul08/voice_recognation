# ASR-With-Whisper-and-Wave2Vec
This project aims to learn build Automatic Speech Recognition (ASR) or Voice Recognition using pretrained models Whisper and Wave2Vec from Indonesia AI NLP Bootcamp. The project was develop by collaborate NLP Team A. In this project we will fine-tune Whisper from scratch which mean without using weights from pretrained and compare it with Whisper that already fine-tuned and Wav2Vec.

# Detail Files
- EDA.ipynb: Jupyter notebook containing EDA.
- whisper_fine_tuning.ipynb: Jupyter notebook containing fine-tuning from scratch without using weights from pretrained and also comparing it with whisper model using weights from pretrained.
- Voice Recognition using Wave2Vec and Whisper.pdf: Final Powerpoint summarizing the whole process and results.
- wav2vec_inferencing_only.ipynb: Jupyter notebook containing the evaluation with the existing dataset of the Wave2Vec model loaded directly using the pretrained model.
- README.md: file containing the project description and brief documentation.

# Additional Information
- Dataset Resources: https://huggingface.co/datasets/PolyAI/minds14
- Pretrained Model: openai/whisper-tiny
- Language: En-US and En-AU

# summary of experiment
The fine-tuned whisper NemesisAlm/whisper-tiny-en model is the best performing model for EN-US and EN-AU as evidenced by the BLEU score above 60% with an average inference time above 1.2 seconds/prediction.
The facebook/wav2vec2-base-960h model is the model with the best efficiency because the inference process for EN-US and EN-AU on average only takes under 1 second/prediction.
