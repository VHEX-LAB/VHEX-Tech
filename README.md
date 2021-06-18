# VHEX-Tech-NLP
prof.Chung's NLP whitesheet for RAPA lab

## 1. 작성일시
2021.05.31
## 2. 작성자 정보(팀)
한승현(VHex.Tech)
## 3. 작성내용
### 3.1 notebook - binarysentiment.ipynb
Binary sentiment analysis for Korean Documents using Bert  
**3.1.1 dependancy**  
OS : windows 10  
Languages : Python 3.7.**  
External modules : see dependency.txt  
External dataset : https://github.com/e9t/nsmc  
**3.1.2 GPU setup**  
Torch : 1.8.1  
CUDA : 11.1  
see https://pytorch.org/get-started/locally/  
**3.1.3 how to run**  
run BinarySentiment.ipynb with jupyter notebook/jupyter lab  
### 3.2 notebook - voicetospeech.ipynb
Voice recognition for local files with local files  
**3.1.1 dependancy**  
OS : windows 10  
Languages : Python 3.7.**  
for SST, we've used google cloud api(https://cloud.google.com/speech-to-text), which requires specific blueprint, to follow what i can do, you'll need to sign in gcloud console  
**3.1.2 GPU setup**  
no need  
**3.1.3 how to run**  
run ViucetoSpeech.ipynb with jupyter notebook/jupyter lab  
### 3.3 streaming - streaming.py
voice recognition for 'streaming' locally  
**3.1.1 dependancy**  
OS : Windows 10  
Languages: python 3.7.**  
Installation : http://portaudio.com/docs/v19-doxydocs/tutorial_start.html  
for SST, we've used google cloud api(https://cloud.google.com/speech-to-text), which requires specific blueprint, to follow what i can do, you'll need to sign in gcloud console  
Externals: pyaudio requires specific installation, see (https://www.youtube.com/watch?v=AKymlea8sYM)  
