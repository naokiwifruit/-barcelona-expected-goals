# Expected Goals (xG) for FC Barcelona
This repo is building as expected goals (xG) model for FC Barcelona from StatsBomb event data.

**NOTE**: This model is trained with shot data of FC Barcelona only since StatsBomb open data is limited to the match Messi has played. Therefore this model should be utilized only for Barca's shot data Messi has played and does not have an generalization ability toward another shot data.

## Dependency
Python 3.7.4

Python libraries:
- numpy 1.16.5
- pandas 0.25.1
- matplotlib 3.1.0
- seaborn 0.9.0
- scikit-learn 0.21.3
- lightgbm 2.3.0
- category_encoders 2.1.0
- pyodbc 4.0.27
- tqdm 4.0.27
- statsbomb 0.3.0

## Setup
Install required Python libraries.
~~~
$ pip install -r ./requirements.txt
~~~

## Usage
Check jupyter notebooks.

## Articles
1. NAOKI『MSN時代のバルセロナのゴール期待値を算出する【バルサxG 結果編】』[note.com](https://note.com/naokiwifruit/n/n9a1b29401c1e) (2019)
2. NAOKI『バルセロナのシュートデータを理解する【バルサxG 可視化編】』[note.com](https://note.com/naokiwifruit/n/n73b5017e72d0) (2019)
3. NAOKI『バルセロナのゴール期待値をLightGBMで予測する【バルサxG モデル構築編】』[note.com]() (2019)

## References
1. StatsBomb, "StatsBomb Open Data" [GitHub](https://github.com/statsbomb/open-data) (2019).
![StatsBomb Logo](img/stats-bomb-logo.png)
2. imrankhan17, "StatsBomb JSON parser" [statsbomb 0.3.0](https://pypi.org/project/statsbomb/) (2019).