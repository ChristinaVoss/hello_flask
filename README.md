# Hello Flask

### App structure

<img width="483" alt="Screenshot 2022-05-12 at 09 41 49" src="https://user-images.githubusercontent.com/20923607/168029847-bdb95508-6c63-4344-83da-9bb52140a601.png">


### Setup

If you have not installed Python3, [please do](https://www.python.org/downloads/).

First create and activate some form of environment to store your dependencies. I like [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html):

```
$ conda create -n myenv python=3.7

$ conda activate myenv
```

**Or** just use Pythons built in environments:

```
$ python3 -m venv venv

$ . venv/bin/activate
```

Then install Flask

`$ pip install Flask`

### Run the app

`$ flask run`

You should now be able to see "Hello Flask!" in your browser window (at http://127.0.0.1:5000) 
