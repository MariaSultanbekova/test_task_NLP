# Всем привет!
В этом проекте я буду создавать алгоритм, который будет проверять,
что в диалоге с клиентом менеджер поздоровался,
представил себя и свою компанию и попрощался. Эти реплики нужно извлекать.

Для начала, я решила попробовать решить задачу с помощью билиотек NLTK и Pymorphy2. Разбила предложение на токены(отдельные слова) 
и разметила части речи. Результаты были не очень 😅 Имена парсер от pymorphy2 нашел, но названия компаний выделить не получилось.
Тогда я вспомнила про библиотку spacy. Подключить русский язык оказалось нельзя, тогда я решила переводить предложения на английский 
с API от google translate.

Spacy тоже не помогла в этой задаче:
![head](https://github.com/MariaSultanbekova/test_task_NLP/blob/master/spacy_results.png)
