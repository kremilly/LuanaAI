
# Luana AI

## Project Overview

Welcome to the Luana AI Assistant project! This project leverages various Python libraries to create a comprehensive AI assistant capable of performing a wide range of tasks, from web scraping and data processing to natural language understanding and interaction with various web services.

## Features

- **Web Scraping and Parsing**: Utilizing `beautifulsoup4` for extracting information from web pages.
- **Web Frameworks**: Powered by `Flask` and `Django` for web-based functionalities.
- **Google Cloud Integration**: Incorporation of Google Cloud services like Firestore and Storage for data storage and retrieval.
- **Machine Learning and AI**: Implementing `scikit-learn`, `tensorflow`, and `torch` for various AI and machine learning capabilities.
- **Natural Language Processing**: Utilizing `nltk` and `SpeechRecognition` for processing and understanding natural language.
- **Database Interaction**: Connecting with databases using `mysql-connector-python` and `pymongo`.
- **Task Automation**: Automating tasks with `PyAutoGUI` and `pywhatkit`.

## Requirements

This project requires several Python packages to function. The dependencies are listed in the `requirements.txt` file:

```
asgiref==3.4.1
backports.entry-points-selectable==1.1.0
beautifulsoup4==4.10.0
CacheControl==0.12.6
cachetools==4.2.4
certifi==2021.10.8
cffi==1.15.0
charset-normalizer==2.0.7
click==8.0.3
colorama==0.4.4
comtypes==1.1.10
cycler==0.10.0
distlib==0.3.3
Django==3.2.8
docutils==0.18
et-xmlfile==1.1.0
filelock==3.3.2
firebase-admin==5.0.3
Flask==2.0.2
google-api-core==2.1.1
google-api-python-client==2.27.0
google-auth==2.3.0
google-auth-httplib2==0.1.0
google-auth-oauthlib==0.4.6
google-cloud-core==2.1.0
google-cloud-firestore==2.3.4
google-cloud-storage==1.42.3
google-crc32c==1.3.0
google-resumable-media==2.0.3
googleapis-common-protos==1.53.0
grpcio==1.41.0
gunicorn==20.1.0
httplib2==0.20.1
idna==3.3
imap-tools==0.49.1
itsdangerous==2.0.1
Jinja2==3.0.2
joblib==1.1.0
keras==2.6.0
Kivy==2.0.0
kivy-deps.angle==0.3.0
kivy-deps.glew==0.3.0
kivy-deps.sdl2==0.3.1
Kivy-Garden==0.1.4
kivymd==0.104.2
kiwisolver==1.3.2
mariadb==1.0.8
MarkupSafe==2.0.1
matplotlib==3.4.3
MouseInfo==0.1.3
msgpack==1.0.2
mysql-connector-python==8.0.27
nltk==3.6.5
numpy==1.21.3
oauthlib==3.1.1
openai==0.11.0
opencv-python==4.5.4.58
openpyxl==3.0.9
packaging==21.0
pandas==1.3.4
pandas-stubs==1.2.0.35
Pillow==8.4.0
platformdirs==2.4.0
playsound==1.3.0
proto-plus==1.19.5
protobuf==3.19.0
psutil==5.8.0
pyasn1==0.4.8
pyasn1-modules==0.2.8
PyAudio @ file:///C:/Users/theem/Downloads/PyAudio-0.2.11-cp39-cp39-win_amd64.whl
PyAutoGUI==0.9.53
pycparser==2.20
pycryptodome==3.11.0
PyGetWindow==0.0.9
Pygments==2.10.0
pyimgur==0.6.0
pymongo==3.12.1
PyMsgBox==1.0.9
pyparsing==2.4.7
pyperclip==1.8.2
pypiwin32==223
PyRect==0.1.4
PyScreeze==0.1.28
python-dateutil==2.8.2
python-dotenv==0.19.1
pyttsx3==2.90
pytweening==1.0.4
pytz==2021.3
pywhatkit==5.1
pywin32==302
regex==2021.10.23
requests==2.26.0
requests-oauthlib==1.3.0
riotwatcher==3.2.0
rsa==4.7.2
scikit-learn==1.0
scipy==1.7.1
six==1.16.0
sounddevice==0.4.3
soupsieve==2.2.1
SpeechRecognition==3.8.1
spotipy==2.19.0
sqlparse==0.4.2
threadpoolctl==3.0.0
torch==1.10.0+cu113
torchaudio==0.10.0
torchvision==0.11.1+cu113
tqdm==4.62.3
tweepy==4.1.0
typing-extensions==3.10.0.2
uritemplate==4.1.1
urllib3==1.26.7
virtualenv==20.9.0
vosk==0.3.31
Werkzeug==2.0.2
wikipedia==1.4.0
```

## Installation

To get started with this project, follow these steps:

1. **Clone the repository**:

   ```sh
   git clone https://github.com/yourusername/my-old-ai-assistant.git
   cd my-old-ai-assistant
   ```
2. **Create a virtual environment**:

   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. **Install the required packages**:

   ```sh
   pip install -r requirements.txt
   ```

## Usage

Once the setup is complete, you can run the AI assistant using the following command:

```sh
python main.py
```

Make sure to configure any necessary API keys and environment variables in a `.env` file as required by the services you are using (e.g., Google Cloud, Firebase, etc.).

## Contributing

We welcome contributions to the My Old AI Assistant project! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
