# Project Status MVP

Recipe Finder is currently in the proccess of moving the databse to Mongodb and parsing pluralization on ingredients/recipes

# recipeFinder

Recipe Finder is web application allowing you to keep track of ingredients you have and display all the possible recipes you can try.

## Installation

requirements [pipenv](https://pypi.org/project/pipenv/) & python3

```bash
git clone https://github.com/JayKim97/recipeFinder.git
cd recipeFinder/ocr_server
pipenv shell
pipenv install --ignore-pipfile
python3 app.py
```

## Usage

Upload image of your recipt it will show all the recipes you can create.

<img src="https://github.com/JayKim97/recipeFinder/blob/main/scraper/readme.png" width="400">

## Current Features

Current status: MVP
Recipe Collections

<ul>
  <li>Collected 7000+ recipes</li>
  <li>Data cleaned and extracted all ingredients</li>
</ul>

Features

<ul>
  <li>Recipt image recognition for grocery</li>
  <li>Recipe search using user ingredients</li>
</ul>

## Project Status

Development of recipe finder is currently put on hold

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
