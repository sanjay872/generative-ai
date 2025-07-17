# Audio Translation

Model used is whisper-1 to translate audio into other given language.

## Setup

- create a .env file with open api key (OPENAI_API_KEY).
- create a new environment and install all required packages.
- Keep a audio file Recording.mp3 to test demo.py.

## Run
Run demo.py for testing connection with the model, it will upload exisiting audio file and get input.
```bash
python demo.py
```

Run app.py
```bash
python app.py
```
open localhost:8080.