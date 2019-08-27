Задачи обработки естественного языка (NLP)
==========================================

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Набор ноутбуков, в которых решаются различные задачи обработки естественного языка (NLP).

## 1. [Определение токсичных комментариев с помощью нейронной сети](https://github.com/blanchefort/text_mining/blob/master/toxic_comments.ipynb)
Задача бинарной классификации текста: разделение комментариев на токсичный / нетоксичный. Нейросеть реализована с помощью фреймворка Flair.

Используемые технологии:
* Эмбеддинг BPE.
* Нейронная сеть bidirectional GRU.

## 2. [Определение тональности текста](https://github.com/blanchefort/text_mining/blob/master/text_sentiment_bpe.ipynb)
Бинарная классификация комментариев на: положительный / отрицательный. Преобразование текстов в векторное предствление осуществляется с помощью модели Byte Pair Embeddings. Модель реализована на фреймворке Flair.
