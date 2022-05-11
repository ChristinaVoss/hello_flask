# Hello Flask

**Setup**

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

**Run the app**

`$ flask run`

You should now be able to see "Hello Flask!" in your browser window (at http://127.0.0.1:5000) 
