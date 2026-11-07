# ХакатонХард

Общий репозиторий команды для работы над проектом хакатона.

## Подключение

```bash
git clone https://github.com/closqee/hackathon-hard.git
cd hackathon-hard
```

## Совместная работа

Перед началом работы получите последние изменения и создайте отдельную ветку:

```bash
git switch main
git pull --ff-only
git switch -c feature/my-task
```

После изменений сделайте коммит, отправьте ветку и откройте Pull Request на GitHub:

```bash
git add <изменённые-файлы>
git commit -m "Описание изменений"
git push -u origin feature/my-task
```

Для отправки веток в этот репозиторий владелец должен добавить участника в **Settings → Collaborators**. Без приглашения можно работать через fork и Pull Request.

Не добавляйте в репозиторий пароли, токены и локальные файлы с секретами.
