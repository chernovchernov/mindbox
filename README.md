# Mindbox task

В этом файле определен деплоймент веб-приложения, который содержит:

- Метаданные деплоймента, такие как название и метки
- Спецификацию деплоймента, которая включает в себя:
-- Количество реплик (4 в данном примере)
-- Селектор для выбора подов, управляемых этим деплойментом
-- Шаблон пода, который будет использоваться для создания реплик
- Спецификацию контейнера, который содержит:
-- Название контейнера
-- Образ Docker
-- Запрашиваемые ресурсы (CPU и память)
-- Порты, на которые будет прослушивать контейнер
-- Настройки для проверки готовности (readinessProbe) и живучести (livenessProbe) контейнера
-- Переменные среды
