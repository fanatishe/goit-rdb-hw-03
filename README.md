# Домашнє завдання 2 — UCI Adult / Census Income

## Файли
- `hw3.ipynb` — основний Google Colab notebook.
- `requirements.txt` — залежності для середовища Python.

## Запуск
1. Завантажте notebook у Google Colab.
2. Оберіть Runtime → Restart session and run all.
3. Notebook автоматично завантажує офіційний `adult.data` з UCI, формує CSV, запускає `pgserver`, завантажує CSV через PostgreSQL `COPY FROM STDIN` і виконує SQL-аудит та EDA.
4. Переконайтеся, що остання клітинка завершилася повідомленням про успішні перевірки.

## Dataset
UCI Adult: https://archive.ics.uci.edu/dataset/2/adult
Файл: https://archive.ics.uci.edu/ml/machine-learning-databases/adult/adult.data
Цитування: Becker, B. & Kohavi, R. (1996). Adult [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5XW20
Ліцензія: CC BY 4.0.

Notebook використовує лише тренувальний файл `adult.data` (32 561 рядок), без об'єднання з `adult.test`.
