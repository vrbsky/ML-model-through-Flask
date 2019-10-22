# Installation
1. Download the repo
2. Run one of the installation scripts
    - `install_win.bat` for Windows
    - `install_unix.sh` for Unix systems

This will create a python virtual environment and install the required packages (in `requirements.txt`).

# Usage
To run the website, execute the `predictor_app.py` file by navigating into its directory and running the following command.
```bash
$ python predictor_app.py
```

I am not currently sure if you do need to activate the virtual environment created during the installation step above.

# Reference
This website is based on a github repo available [here](https://github.com/jeremyrchow/Harassment-Classifier-App). See below the description of the original referenced project.

# Sample Flask deployment of machine learning models with a GUI as a website
This repo shows a sample use of deployment of models using Flask. A website front-end can interact with the model.

# Original referenced project - Twitch Harassment Classifier Website
Showcases harassment classifier trained on 160,000+ Wikipedia comments from a Kaggle dataset. Primary goal is to pipe live Twitch chat from a streaming channel and classify comments for toxicity in real time.

Model is currently live and available on this [Twitch channel](https://www.twitch.tv/datatestdummy/). To see predictions, type toxic chat into the chatbar on the right of the screen. Note: Website may take 10 seconds to load if its heroku node is currently sleeping due to inactivity.

By Jeremy Chow and Randy Macaraeg
