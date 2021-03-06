[<к содержанию](./readme.md)

## git branch
**git branch** - это своего рода "менеджер веток". Она умеет перечислять ваши ветки, создавать новые, удалять и переименовывать их.

При запуске без параметров, вы получите простой список имеющихся у вас веток

```bach=
git branch
* main
```

Чтобы посмотреть последний коммит на каждой из веток, выполните команду `git branch -v`

```bach=
git branch -v
* main 0572e21 update md
```

Чтобы создать ветку выполните команду `git branch` с названием новой ветки yfghbvth `develop`

```bach=
git branch develop
git branch
develop
* main
```
Чтобы переименовать ветку выполните команду `git branch -m` после комады пишем новое название. при этом нужно находиться в той ветке, которую хотите переименовать.

```bach=
git branch
* develop
main
git branch -m myfix
git branch
* myfix
main
```

Чтобы удалить ветку выполните команду `git branch -d` с названием ветки, котурую хотите удалить. При этом нужно нахоться в другой ветке.

```bach=
git branch -d myfix
git branch
* main
```