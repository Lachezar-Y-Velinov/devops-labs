# Runbook

> Fill in every TODO with exact commands. / Попълнете всяко TODO с точни команди.

## Start locally / Локално стартиране

python3.12 -m venv .venv
source .venv/bin/activate          # Windows: .venv\Scripts\activate
pip install -r requirements-dev.txt

uvicorn app.main:app --reload

## Check that it works / Проверка, че работи

## кой адрес отваряте и какво трябва да видите?
Приложението е на http://127.0.0.1:8000
## Run the tests / Тестове

pytest
ruff check .

## When something breaks / Когато нещо се счупи

TODO: the first three things you check. / първите три неща, които проверявате.
Гледа се терминала какво показва за да се види точно къде се е счупило
Поглежда се къде е проблема за да се поправи
Правим тестове с pytest и ruff check .

