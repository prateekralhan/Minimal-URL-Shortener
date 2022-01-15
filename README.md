# ✨ Minimal URL Shortener 🔗 [![Project Status: Active](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active) [![](https://img.shields.io/badge/Prateek-Ralhan-brightgreen.svg?colorB=ff0000)](https://prateekralhan.github.io/)
A minimalistic flask based webapp to shorten your URLs! :wink:

### Live app can be found [here](https://urlxmin.herokuapp.com/)

## Installation:
Simply run ***pip install -r requirements.txt*** to install all the necessary dependencies.

## Usage:
1. Create **.env** file contents with the following contents:

```
SECRET_KEY= <Enter your secret key here>
DATABASE_URL=sqlite:///shorty.db
APP_SETTINGS=config.DevelopmentConfig
FLASK_APP=core
```

2. Clone this repository and navigate to the root directory.
3. Run the command : ***python main.py*** and it will launch the webapp in your browser.

![1](https://user-images.githubusercontent.com/29462447/148431403-833a77d5-59a6-465e-8e8b-83d80e6d52a8.png)


![2](https://user-images.githubusercontent.com/29462447/148431628-311fb4d0-76ea-4d6f-8844-74f595962fdd.png)
