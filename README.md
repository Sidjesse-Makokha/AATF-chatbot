# AATF-chatbot
In CMD, 
input:
git clone https://github.com/Sidjesse-Makokha/AATF-chatbot.git
cd AATF-chatbot
python -m venv venv
venv\Scripts\activate
(venv) pip install Flask torch torchvision nltk
Run
(venv) python
>>> import nltk
>>> nltk.download('punkt')
>>> quit()
(venv) python train.py
(venv) python chat.py
