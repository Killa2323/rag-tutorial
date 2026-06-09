# Submission

## Ссылка на репозиторий с заданием

- Repo URL: https://github.com/Killa2323/RAG-hw

## Автор

- ФИО / ник: Killa2323

## Комментарий

Учебный RAG по деловым и экономическим новостям Gazeta.ru (датасет IlyaGusev/gazeta, рубрики business/financial/realty/techzone). Полный pipeline: ingestion -> chunking -> TF-IDF индекс -> retrieval (cosine top-k) -> demo-ответ с источниками -> Streamlit UI; есть явный отказ при отсутствии релевантного контекста. Корпус: 1500 статей -> ~11154 чанка. Тесты: 11 (pytest), все проходят. Demo: 3 ответа + 1 отказ. Реализованные улучшения: регулировка top-k/порога и подсветка слов в Streamlit, русские стоп-слова + биграммы в TF-IDF (см. IMPROVEMENTS.md).
