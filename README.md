Flask app for training vgg16_model solar panel classification/detection model. Missing some data sources

Env
- python3 -m venv venv
- source venv/bin/activate
- pip install -r requirements.txt

How to start: 
1. cd to DeepSolar foler 
2. export FLASK_ENV=development & export FLASK_APP=DeepSolarisFlask.py
3. flask run

Issue:
- Getting `zsh: illegal hardware instruction flask run` - appears to be [due to my use of M1 Mac](https://github.com/apple/tensorflow_macos/issues/143)