# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #3 выполнил(а):
- Уткин Никита Александрович
- РИ231113
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Цель работы
Разработать оптимальный баланс нанесения урона оружием для игры Save RTF (конами-код для начисления денег / жизней и т.д.)

## Задание 1. Начало работы с прототипом
### Ознакомьтесь с презентацией третьей лекции, оцените структуры игры Dragon Picker. Скачайте и ознакомьтесь с прототипом игры Dragon Picker на движке Unity. Запустите игровую сцену, проанализируйте движение дракона:

# Какие переменные влияют на движение дракона на сцене? Укажите эти переменные.
-Скорость дракона и случайное значение для изменения движения
# Какие переменные влияют на сложность игры на сцене? Укажите эти переменные.
-Скорость дракона, частота появления яий и их скорость

## Задание 2. Начало работы с шаблоном google-таблицы для балансировки игры
### Как может быть использован шаблон таблицы для визуализации изменения уровней сложности в игре Dragon Picker?
Может быть использоно чтобы отследить как меняются переменные "баланса" в зависимости от каждого уровня

## Задание 3. Задания к работе
### Задание 1. Предложите вариант изменения найденных переменных для 10 уровней в игре. Визуализируйте изменение уровня сложности в таблице. 
В качестве параметров усложнения было выбрано - скорость дракона, частота создания яиц(уменьшить промежуток межди их созданием) и кол-во щитов. Для проверки вариантов первые 3 варианта - это усложнение только по 1 из параметров, а все остальные палвное усложение сразу по всем

[(ссылка на таблицу)](https://docs.google.com/spreadsheets/d/16AX-HqlI6OAN4arEQZ_SKQ5ygpzQcHPkrLtao4_j8Qk/edit?gid=0#gid=0)


После проверки, можно сказать что самым оптимальным вариантом был 8 или 10 уровни(самый приятный 10, но 1 щит маловато)
### Задание 2. Создайте 10 сцен на Unity с изменяющимся уровнем сложности.
  Приложил unitypackage в форму
## Выводы

Я научился работать с параметрами баланса, визуализировать их, расчитывать, а также применять изменения в Unity и сравнивать их.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
