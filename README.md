<p align="center">
  <img src="https://krot.info/uploads/posts/2022-03/1646870673_11-krot-info-p-smeshnie-kovri-na-stenu-smeshnie-foto-14.jpg" align="middle"  width="600" />
</p>


<h2 align="center">
  GennaDIY
</h2>

<h4 align="center">

![1](https://img.shields.io/badge/python-3.10.6+-aff.svg)
![2](https://img.shields.io/badge/os-linux%2C%20win%2C%20mac-pink.svg)
![3](https://img.shields.io/github/stars/NikitaVenediktov/GennaDIY?color=ccf)
![4](https://img.shields.io/github/v/release/NikitaVenediktov/GennaDIY?color=ffa)

</h4>

-----------------------------------------------

<h4 align="center">
  <a href=#features> Features </a> |
  <a href=#installation> Installation </a> |
  <a href=#quick-start> Quick Start </a> |
  <a href=#community> Community </a>
</h4>

-----------------------------------------------

**GennaDIY** он вам покажет откуда готовилось нападение. Готовое решение для вас!



## &#128204;Features

### &#128642;Под капотом  (Мы предоставляем сценарий):
* пук-пук


###  	&#128270; Нейронная поисковая система


#### ❓ Настройка подготовки данных

Для тренировки модели можно использовать удобный папплайн `train.py`
```python
# Generate PRE pipeline

```

#### 💌 NLTK и spaCy 

Пункт в разработке


#### ⚡ Пример работы

```python
Введите название компании:
bridgestone

```

```python


#### 🚀 Метрики

Пункт в разработке

## &#128204;Installation

### Используемые библиотеки

* python >= 3.10
* numpy >= 1.23.4
* pandas >= 1.5.0
* scikit-learn >= 1.1.2
* notebook >= 6.5.1
* tables >= 3.7.0
* gensim >= 4.2.0
* nltk >= 3.6.5
* joblib >= 1.1.0

Через requirements.txt для pip:
```python
pip install -r requirements.txt
```
С помощью [Poetry](https://python-poetry.org) устанавливаются все зависимости. Кроме pip можно использовать [Homebrew](https://formulae.brew.sh/formula/poetry) или [Conda](https://anaconda.org/conda-forge/poetry).
``` python
git clone https://github.com/NikitaVenediktov/GennaDIY.git
pip install poetry
poetry install
```


## &#128204; Quick Start
> Сценарий 1 - Обучаем на ваших данных
 
 
 
В папку `/data` добавляете свой `train.csv`

```python
>>>train()
>>>ranking()
```
Программа формирует файлы весов(`embeddings.h5`, `logit.joblib`, `word2vec.model`) и добавляет в `/data`.
Трейн лежит на [диске](https://drive.google.com/file/d/1e9bdr7wcQX_YBudQcsKj-sMoIGxQOlK4/view)

> Сценарий 2 - используем наши веса

В папку `/data` добавляете свой `embeddings.h5`, `logit.joblib`, `word2vec.model`

```python
>>>ranking()
```
Они лежать на [диске](https://drive.google.com/drive/folders/1b3BEHNyzqOKzoOP4HaH4zU5SXu3_lwOD?usp=sharing)

## &#128204;Community

### Расти вместе с AI Talent Hub!
На базе [AI Talent Hub](https://ai.itmo.ru/) Университет ИТМО совместно с компанией Napoleon IT запустил образовательную программу «Инженерия машинного обучения». Это не краткосрочные курсы без практического применения, а онлайн-магистратура нового формата, основанная на реальном рабочем процессе в компаниях.

Этот проект создан в рамках второго задания по курсу: "Глубокое обучение на практике"

Мы команда ViN:
* [Виктор](https://t.me/anoninf)
* [Илья](https://t.me/sadinhead)
* [Никита](https://t.me/space_apple)

<details><summary> &#128516; Шутейка </summary>
<p>

![Jokes Card](https://readme-jokes.vercel.app/api)

</p>
</details>

## Цитирование 

Если вы используете GennaDIY в своих исследованиях, рассмотрите возможность цитирования
```python
@misc{=GennaDIY,
    title={=GennaDIY: An Easy-to-use and High Performance CLI},
    author={ViN Contributors},
    howpublished = {\url{https://github.com/NikitaVenediktov/GennaDIY}},
    year={2022}
}
```

## Благодарность

- [Сравниваем работу open source Python — библиотек для распознавания именованных сущностей](https://habr.com/ru/post/502366/)
## Лицензия

 [The MIT License](https://opensource.org/licenses/mit-license.php).