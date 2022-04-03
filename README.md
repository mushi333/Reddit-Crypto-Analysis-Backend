# Reddit Crypto Analysis Tool
This is a fun pet project to explore the recommendations of what Reddit suggests buying in the crypto field. The main
gist is to go against the grain here and see if the prices truly do fall/rise after a suggestion that occurs.

## Requirements
* Python 3.9.0
* fastapi 0.75.0
* uvicorn 0.17.5
* Pycharm (suggested)

## Installation
```
pip install 'fastapi==0.75.0'
pip install 'uvicorn==0.17.5'
```

## Running Installation
```
uvicorn main:app --reload
```
Then open your browser to "127.0.0.1:8000"

## Online Demo
Currently, there is no online demonstration. But the plan is to use Heroku to host this python app and Netlify for the 
frontend JavaScript web app.

## Design
Using FastAPI, we call a Reddit API to scan the current month's top voted post. We then scan the post to see if it is 
a good or bad suggestion by them and recommend the opposite. We will store this in a persistent relational database and
the frontend web application will show this information in a clean manner.

Link to frontend repository - N/A.

## Credit
N/A

## License
MIT License.
