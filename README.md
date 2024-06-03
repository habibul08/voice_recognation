# ASR-With-Whisper-and-Wave2Vec
This project aims to build Automatic Speech Recognition (ASR) or Voice Recognition project using Whisper and Wave2Vec from Indonesia AI NLP Bootcamp. The project was develop by collaborate NLP Team A. In this project we will fine-tune Whisper from scratch which mean without using weights from pretrained and compare it with Whisper that already fine-tuned and Wav2Vec.

#Detail Files
EDA.ipynb: Notebook Jupyter yang berisi EDA.
whisper_fine_tuning.ipynb: Notebook Jupyter yang berisi fine-tuning dari awal tanpa menggunakan weights dari pretrained dan juga membandingkannya dengan model whisper yang menggunakan weights dari pretrained.
Voice Recognition using Wave2Vec and Whisper.pdf: Final Powerpoint terkait ringkasan dari keseluruhan proses serta hasil.
wav2vec_inferencing_only.ipynb: Notebook Jupyter yang berisi evaluasi dengan dataset yang ada dari model Wave2Vec yang di load secara langsung menggunakan model yang sudah di pretrained.
README.md: file yang berisi deskripsi proyek dan dokumentasi singkat.

# Additional Information
Dataset Resources: https://huggingface.co/datasets/PolyAI/minds14
Pretrained Model: openai/whisper-tiny
Language: En-US and En-AU

# summary of experiment
The fine-tuned whisper NemesisAlm/whisper-tiny-en model is the best performing model for EN-US and EN-AU as evidenced by the BLEU score above 60% with an average inference time above 1.2 seconds/prediction.
The facebook/wav2vec2-base-960h model is the model with the best efficiency because the inference process for EN-US and EN-AU on average only takes under 1 second/prediction.
