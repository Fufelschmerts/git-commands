# git reflog

**git reflog** позволяет вам просмотреть полную историю всех изменений указателей, даже если вы переключались между различными коммитами или ветками. 

```bash=
$ git reflog
```

Это может быть полезно, если вы хотите восстановить состояние репозитория или отследить, когда и какие операции были выполнены.

**Пример вывода команды git reflog:**
```bash=
HEAD@{0}: commit: Update README.md
HEAD@{1}: checkout: moving from feature-branch to master
HEAD@{2}: commit: Add new feature
HEAD@{3}: commit: Fix bug
```
