# Record video of OpenAI gym environment demo.
The goal of this project is to demonstrate recording a video of an OpenAI gym.
```
$ python3 -m venv env
$ source env/bin/activate
$ pip install -r requirements.txt
$ brew install ffmpeg
$ python cartpole.py
```
This will put the video's of the runs in the directory `./video`.