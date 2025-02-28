


# LMM_robotarm



## JM part require
cuda 

cudnn

### windows OS
https://angelplayer.tistory.com/351


### Ubuntu OS
sudo apt update && sudo apt upgrade -y
sudo apt install ffmpeg -y
sudo apt-get install vlc
sudo apt-get install portaudio19-dev
sudo apt-get install mpg123


### require
pip install torch
pip install openai-whisper
pip install --upgrade --no-deps --force-reinstall git+https://github.com/openai/whisper.git
pip install PyAudio
pip install pydub
pip install gtts
pip install PyQt5



## TM part require

git clone https://github.com/huggingface/transformers.git
cd transformers
pip install .

pip install langchain
pip install langchain-community
pip install sentence-transformers
pip install faiss-cpu

TM/temp/requirements.txt 참고
