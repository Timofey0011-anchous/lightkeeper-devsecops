# Проверка локального результата

Из каталога проекта выполнить:

```bash
git status --short
git rev-list --count main
git branch --list
git log --all --merges --oneline
git log --graph --oneline --all --decorate
git diff --check
git fsck --full
```

Ожидания: рабочее дерево чистое, коммитов не меньше 6, веток 5,
в main есть merge-коммиты, Git не сообщает ошибок целостности.

Для доказательства конфликта:

```bash
git show --remerge-diff ':/fix: разрешить конфликт'
```

GitHub-часть проверяется отдельно после публикации: публичная ссылка,
пять удалённых веток и граф Insights → Network.
Локальный граф не является скриншотом GitHub Network.
