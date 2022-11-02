# INF8245 Kaggle competition

## Installation

Create a virtual environment:
```
$ python3 -m venv env
```
Activate the virtual environment:
```
$ source env/bin/activate
```
Install the requirements:
```
$ pip install -r requirements.txt
```

## Kaggle

(Kaggle API)[https://github.com/Kaggle/kaggle-api]

List competition files:
```
kaggle competitions files inf8245e-fall-2022
```
Download competition files:
```
$ kaggle competitions download -c inf8245e-fall-2022
```
Submit to a competition:
```
kaggle competitions submit -f FILE_NAME -m MESSAGE inf8245e-fall-2022
```
List competition submissions:
```
kaggle competitions submissions inf8245e-fall-2022
```
Get competition leaderboard:
```
kaggle competitions leaderboard inf8245e-fall-2022
```
