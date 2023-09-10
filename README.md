# RutubeRecSys
## Рекомендательная система для Rutube (ЦП 2023)

**Идея**: 

1. Для "холодного старта" - заранее собираем топ из актуального видео + топы из 20 популярных категорий. Из них составляем рекомендацию случайным образом, что даёт хорошее разнообразие из популярных видео.

2. Для пользователей у которых есть история — рекомендации рассчитываются ансамблем моделей, с учетом их прошлых просмотров и выставленных эмоций.

## Файлы проекта
[./EDA-final.ipynb](https://github.com/invincible/RutubeRecSys/blob/main/EDA-final.ipynb) Разведочный анализ данных;

[./rutube_tfidf_comments.ipynb](https://github.com/invincible/RutubeRecSys/blob/main/rutube_tfidf_comments.ipynb) Код основного решения;

[./RUTUBE_холодный_старт-2.ipynb](https://github.com/invincible/RutubeRecSys/blob/main/RUTUBE_%D1%85%D0%BE%D0%BB%D0%BE%D0%B4%D0%BD%D1%8B%D0%B9_%D1%81%D1%82%D0%B0%D1%80%D1%82-2.ipynb) Решение для холодного старта;

[./submission_.csv](https://github.com/invincible/RutubeRecSys/blob/main/submission_.csv) Файл с рекомендациями;
