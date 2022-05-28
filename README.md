# MovieDome
Movie Recommendation System created using Collaborative Filtering in website and Content based Filtering in ML algorithm such as K Nearest Neighbours.You can get recommended movies by Movie Name Or Genre.

## Download the following Datasets from [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
1. credits.csv
2. ratings.csv
3. movies_metadata.csv

## Steps to run the project
1. Clone or download this repository to your local machine.
2. Get your API key from https://www.themoviedb.org/ and replace `YOUR_API_KEY` with your API key in `static/movieNameRec.js` file.
3. Activate your virtualenv. (if any)
4. Run the command `pip install -r requirements.txt` to install the libraries in requirements.txt file
5. Open your terminal/command prompt from your project directory and run the command `python main.py`.

## Flowchart
<img width="2994" alt="Movie Dome" src="https://user-images.githubusercontent.com/76651398/170763569-a95af6c5-13be-43d7-babc-77b0502fab9f.png">

## Deployment
The application deployed can be accessed from [here](https://movie-dome.herokuapp.com/)

## Presentation
You can refer the ppt from [here](https://github.com/Kavita-Dhamot/MovieDome/files/8791550/MovieDome.pptx)

## Resources
You can go through [this](https://datajobs.com/data-science-repo/Recommender-Systems-%5BNetflix%5D.pdf) to know more about the algorithm.

## Extra Error
If you encounter `Python/Docker ImportError: cannot import name 'json' from itsdangerous` then just put `itsdangerous==2.0.1` in your `requirements.txt` and run the command `pip install -r requirements.txt` to update your virtualenv.
