## Обучение модели классификации комментариев
### Инструменты
Pandas, BERT, nltk, tf-idf
### Что делаем

Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

### Итоги

Лемматизировали данные и избавились от лишних симвлов для более качественной работы алгоритмов.  Подгрузили предобученную моедль Bert и создали эмбендинги, получив таким образом признаки для модели логистической регрессии, которая, в конечном итоге, и классифицирует данные. 
