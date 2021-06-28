# Шаблон РПЗ по НИРС или ВКР для ИУ8 

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/CatInCosmicSpace/latex-template/CI?label=CI&logo=github)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/CatInCosmicSpace/latex-template/CI?label=CTAN&logo=github)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/CatInCosmicSpace/latex-template/CI?label=CTAN&logo=latex)

Пакет подключается сразу и не требует скачивания! 
Пример заполнения титульного листа и вообще построения документа можно найти 
в директории `full-example` этого репозитория.

```latex
\documentclass[diploma]{BMSTU-IU8}
```

Шаблон загружается в репозиторий пакетов [CTAN](https://www.ctan.org/)
при тегах на Гитхабе, 
обновление его на всех зеркалах может занять порядка нескольких 
дней.

Использование чего тут есть:
* титульный лист (отдельно для НИРС и ВКР, задаётся опцией для пакета 
`diploma` или `research`);
* содержание;
* термины и определения;
* список источников;
* приложения;
* рисунки;
* таблицы;
* многостраничные таблицы;
* формулы;
* алгоритмы;
* математическая среда - теоремы, определения, следствия, примеры;
* листинги.

Пример, приведённый в директории `full-example`, служит только в качестве примера! 
А пример `example` приводит _минимальный_ пример скомпилированного файла.
Его не нужно скачивать. И этот пример проходит `TestVKR`, исключая замечание 
по количеству страниц.

Чего тут нет (и не будет, потому что это отдельные сущности):
* задания на работу (НИРС или ВКР);
* календарного плана.

Эти части стоит оформить отдельно и вставить в работу, а в своём документе не 
забывайте поменять номер страницы на нужный.

В общем-то, всё, что мне встречалось по ходу оформления отчётов 
(не только своих), собрано здесь.
