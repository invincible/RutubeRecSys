# RutubeRecSys
## Рекомендательная система для Rutube (ЦП 2023)

**Идея**: 

1. Для "холодного старта" - заранее собираем топ из актуального видео + топы из 20 популярных категорий. Из них составляем рекомендацию случайным образом, что даёт хорошее разнообразие из популярных видео.

2. Для пользователей у которых есть история — рекомендации рассчитываются ансамблем моделей, с учетом их прошлых просмотров и выставленных эмоций.

## Файлы проекта
[./EDA-4.ipynb](https://github.com/invincible/RutubeRecSys/blob/main/EDA-4.ipynb) Разведочный анализ данных;

[./rutube_tfidf_comments.ipynb](https://github.com/invincible/RutubeRecSys/blob/main/rutube_tfidf_comments.ipynb) Код основного решения;

[./submission_.csv](https://github.com/invincible/RutubeRecSys/blob/main/submission_.csv) Файл с рекомендациями;
