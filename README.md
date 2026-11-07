# LightKeeper — учёт фонарей и аккумуляторов

Назначение: учёт фонарей, аккумуляторов и их обслуживания.

Учебный проект по дисциплине «Введение в DevSecOps».
Контрольная точка: Git workflow. Автор: Лосев Тимофей Михайлович.

## Индивидуальная тема

Сервис учёта фонарей и аккумуляторов. Пользователь ведёт каталог оборудования,
отмечает исправность и планирует обслуживание.
Тема выбрана как небольшой предметный проект, который можно развивать
в практиках Linux, Docker, Docker Compose и архитектуры.
Уникальность темы внутри группы нужно сверить со списком преподавателя.

## Структура

- `README.md` — назначение и навигация по проекту.
- `project-notes.md` — требования и границы проекта.
- `api-plan.md` — план будущего REST API.

В этой контрольной точке подготовлены документы и примеры данных.
Запускаемое приложение не требуется и пока не реализовано.

## Как изучить проект

1. Прочитать требования в `project-notes.md`.
2. Посмотреть каталог `data/equipment.csv` и `docs/catalog.md`.
3. Изучить операции в `api-plan.md` и пример `data/create-equipment.json`.
4. Открыть `git-conflict.md` для разбора конфликта.

## Состав результата Git

Ветки: `main`, `feature/catalog`, `feature/api-plan`, `docs/usage`, `docs/description`.
Ветки сохранены после слияния, чтобы их можно было показать на проверке.
Команды для просмотра: `git branch`, `git log --graph --oneline --all --decorate`.

## Материалы контрольной точки

- [Разбор реального конфликта](git-conflict.md).
- [Вывод Git при конфликте](docs/evidence/conflict-before.txt).
- [Памятка для защиты](docs/defense.md).
- [Проверка результата](docs/verification.md).
- [Локальный граф истории](docs/git-graph.png) — схема по фактическим родителям коммитов.

## Публичный репозиторий и сдача

- [Репозиторий GitHub](https://github.com/Timofey0011-anchous/lightkeeper-devsecops).
- [Граф веток GitHub Network](https://github.com/Timofey0011-anchous/lightkeeper-devsecops/network).
- [Все ветки](https://github.com/Timofey0011-anchous/lightkeeper-devsecops/branches).
- [История main](https://github.com/Timofey0011-anchous/lightkeeper-devsecops/commits/main/).
- [Коммит разрешения конфликта](https://github.com/Timofey0011-anchous/lightkeeper-devsecops/commit/268cdb7ff02107b1f443735139b911326d09afec).

Все пять веток опубликованы. Для сдачи отправляется ссылка на репозиторий.
Network формируется GitHub; локальная схема истории также доступна
в `docs/git-graph.png`.
