# Adapting Whisper for Lightweight and Efficient Automatic Speech Recognition of Children for On-device Edge Applications

# Work in Progress! 

This paper has been accepted for presentation at the 2025 – Workshop on Child Computer Interaction (WOCCI 2025), a Satellite Workshop of the 2025 Interspeech Conference. I will continue to work and update this GitHub page with the relevant resources. 

## Highlights 

## Summary 
Reliability on cloud providers for ASR inference to support child-centered voice-based applications is becoming challenging due to regulatory and privacy challenges. Motivated by a privacy-preserving design, this study aims to develop a lightweight & efficient Whisper ASR system capable of running on a Raspberry Pi. Upon evaluation of the MyST corpus and by examining various filtering strategies to fine-tune the `tiny.en' model, a Word Error Rate (WER) of 15.9% was achieved (11.8% filtered). A low-rank compression reduces the encoder size by 0.51M with 1.26x faster inference in GPU, with 11% relative WER increase. During inference on Pi, the compressed version required ~2 GFLOPS fewer computations. The RTF for both the models ranged between [0.23-0.41] for various input audio durations. Analyzing the RAM usage and CPU temperature should that the PI was capable of handling both the tiny models, however it was noticed that small models initiated additional overhead/thermal throttling.

## Hugging Face Models 

1. [SatwikDutta/kid-whisper-tiny-en-myst](https://huggingface.co/SatwikDutta/kid-whisper-tiny-en-myst): 

## Citation
