# Ranker - Проект Команды Союз

## Введение

Добро пожаловать в репозиторий проекта "Ranker" от команды Союз. Этот проект включает в себя код, представленный в файле submit.ipynb, который решает задачу ранжирования видео-запросов.

## Описание проекта

Проект направлен на создание модели ранжирования для видео-запросов. Мы используем методы машинного обучения, включая CatBoost, SentenceTransformer и библиотеки Faiss и SHAP.

## Структура репозитория

- submit.ipynb: Jupyter Notebook с основным кодом проекта.
- videos.parquet: Набор данных с информацией о видео.
- automarkup.parquet: Набор данных с автоматической разметкой запросов.
- candidates.index: Файл сформированного индекса для кандидатов.
- ind2videoid.json: Словарь с соответствием индексов идентификаторам видео.
- generated_candidates.parquet: Набор данных с сгенерированными кандидатами.
- features.parquet: Набор данных с признаками видео.
- full_df.parquet: Итоговый набор данных после объединения и предобработки.
- cleared_features.parquet: Очищенные признаки видео (закомментировано в коде).
- ranker.ckpt: Сохраненная модель CatBoostRanker.

## Инструкции по запуску

1. Запустите Jupyter Notebook submit.ipynb.
2. Выполните ячейки по порядку для формирования индекса, обработки данных и обучения модели.
3. Модель сохранится в файл ranker.ckpt.

## Зависимости

Проект использует следующие библиотеки и фреймворки:

- faiss
- numpy
- pandas
- pyarrow
- requests
- sentence_transformers
- shap
- catboost
- matplotlib

## Лицензия

Этот проект распространяется под лицензией [MIT](LICENSE).

## Контакты

Если у вас есть вопросы или предложения, не стесняйтесь связаться с нами:

- Email: domnenko@mail.ru
- Telegram: @domnenko_a_n


Спасибо за использование нашего проекта!
