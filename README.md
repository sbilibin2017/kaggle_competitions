# ПРЕДСКАЗАНИЕ ПОБЕДИТЕЛЯ В ТУРНИРНОЙ ИГРЕ ПО CS:GO

## методы API
<img src="api.png">

1. GET parse_games - запускает парсер PandaScore
2. GET refit_model - обучает модель на новых играх
3. GET teams - словарь с командами, участвовавшими в обучении
4. GET players - словарь с игроками, участвовавшими в обучении
5. GET maps - словарь с картами, участвовавшими в обучении
6. GET metrics - словарь с точностью модели
6. POST prediction  - вероятность победы команды 1

## структура:

```
.
|____ game_in
|____ game_out
|____ game_not_valid
|____ game_preprocessed_split
|____ dictionaries
|____ data
|____ src
    |____ parser.py
    |____ scripts.py
    |____ winner_prediction4map.py
    |____ app.py
|____ requirements.txt
|____ Dockerfile
|____ README.md
|____ api.png

```
