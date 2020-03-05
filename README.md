# Expected Goals (xG) for FC Barcelona
This repo is building an Expected Goals (xG) model for FC Barcelona from StatsBomb event data. 

"Expected Goals (xG)" is a metric which assesses a goal probability for each shooting circumstance. We predicted xGs for all Barca's shots in La Liga 18/19 season by the LightGBM model which was trained with shot data in 04/05-17/18 seasons.

**NOTE**: This model is trained with shot data of FC Barcelona only since StatsBomb open data is limited to the match Messi has played. Therefore this model should be utilized only for Barca's shot data Messi has played and does not have an generalization ability toward another shot data.

## Dependency
Python 3.7.4

Python libraries:
- numpy 1.16.5
- pandas 0.25.1
- matplotlib 3.1.0
- scikit-learn 0.21.3
- lightgbm 2.3.0
- category_encoders 2.1.0
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
1. naokiwifruit『MSN時代のバルセロナのゴール期待値を算出する』[Scientification](https://naokiwifruit.com/2019/12/02/barcelona-expected-goals/) (2019)
2. naokiwifruit『バルセロナのシュートデータを可視化する』[Scientification](https://naokiwifruit.com/2019/12/14/visualize-barcelona-shot-data/) (2019)
3. naokiqifruit『バルセロナのゴール期待値をLightGBMで予測する』[Scientification](https://naokiwifruit.com/2019/12/30/lightgbm-barcelona-expected-goals/) (2019)

## References
1. StatsBomb, "StatsBomb Open Data" [GitHub](https://github.com/statsbomb/open-data) (2019).
![StatsBomb Logo](images/stats-bomb-logo.png)
2. imrankhan17, "StatsBomb JSON parser" [statsbomb 0.3.0](https://pypi.org/project/statsbomb/) (2019).
