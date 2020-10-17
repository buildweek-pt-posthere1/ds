# ds
## File Structure
```
├── ./app_api
│   ├── ./app_api/app.py
│   ├── ./app_api/__init__.py
│   └── ./app_api/predict.py
├── ./code
│   ├── ./code/Code_for_API_Endpoint.ipynb
│   └── ./code/Subreddit_Predictor.ipynb
├── ./Dockerfile
├── ./heroku.yml
├── ./LICENSE
├── ./model
│   ├── ./model/keras_pred_subreddit_model_v5.h5
│   ├── ./model/keras_tokenizer_v5.pickle
│   ├── ./model/sklearn_label_encoder_v5.pickle
│   └── ./model/subreddit_info_cleaned.csv
├── ./Pipfile
├── ./Pipfile.lock
├── ./Procfile
├── ./README.md
├── ./requirements.txt
└── ./runtime.txt

```
# Flask API for reddit - posthere

gaining acces to api via url:
```
https://bw3-posthere.herokuapp.com/
```
(test api)


## pushing model to heroku from command line:
make sure heroku cli is installed ([instructions can be found here](https://devcenter.heroku.com/articles/heroku-cli)).

```
git add .

git commit -m "<message>"

heroku create <appname>

heroku git:remote -a <appname>

git push heroku master
```

## Implementation of docker image for heroku flask app.

TODO

