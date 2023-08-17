# Направление Data Science, профессия ML-инженер NLP-направления MTS AI
##Задание 1. Обучи классификатор, используя открытые данные

Рады, что ты присоединился к команде MTS AI!

Александр, руководитель NLP-девелоперов и твой наставник, попросил тебя подключиться к первой задаче и помочь коллегам с классификацией интентов.

> Привет! В экосистеме МТС есть множество продуктов, и у пользователей иногда возникаютвопросы по их использованию. Они могут обращаться в службу поддержки (чаты) или пытаться самостоятельно найти ответы, вводя поисковые запросы. При этом алгоритм машинного обучения оперативно подхватывает пользовательские запросы и пытается предложить решение. Если алгоритм верно уловил суть, он дает полезный ответ. То есть с помощью описанного выше алгоритма, мы решаем задачу под названием «классификация интентов».
Твоя задача — провести классификацию интентов на основе примеров из предложенного датасета.
Для этого:
1. Обучи классификатор, используя набор фраз из обучающей выборки.
2. Помни, что классификатор должен уметь самостоятельно оценивать, насколько фразы из тестовой выборки похожи на примеры из обучающей, и принять решение, к какому классу отнести в итоге эти запросы.
/b Hints. Для решения задания рекомендую использовать трансформеры, например BERT, чтобы достигнуть высокого качества работы модели на интентах, которые есть в обучении. Спасибо!


### Полезные материалы
● Ссылка на датасет [MASSIVE](https://huggingface.co/datasets/AmazonScience/massive/viewer/en-US/train) (на английском языке), содержащий большое
количество высказываний виртуального помощника Alexa. Обрати внимание, что
датасет содержит 11500 записей в обучающей, 2030 записей — в валидационной и
2970 записей — в тестовой выборках.

● Курс об основах обработки естественного языка на Hugging Face.

### Формат конечного результата
Код с комментариями - вы можете самостоятельно выбрать предпочтительный формат: файл
.ipynb (ноутбук) с описанием или скрипт .py с readme файлом. В любом случае нужны какие-
то комментарии и выводы по полученным результатам.



## Задание 2. Доработай модель с учетом новых вводных
Пришло время поработать над вторым и заключительным заданием. Александр прислал тебе
детали проекта, связанного с доработкой модели, созданной на предыдущем этапе.
>Привет,
Спасибо за отлично проделанную работу по обучению модели!
Как ты знаешь, пользователи не всегда могут формулировать запросы, на которые у
модели есть ответы. Чтобы не вызывать их недовольство, работая заведомо некорректно,
мы должны отлавливать запросы, относящиеся к тем интентам, которые модель не знает,
либо вообще не содержащие в себе интент.
Твоя задача — доработать модель для возможности учета out-of-scope запросов.
Для этого:
1. Используй любые данные (чувствую, что без обогащения нам не обойтись ) и
методы на твое усмотрение. Советую для начала ознакомиться с теми, которые
указаны в полезных материалах во вложении.
2. Предложи варианты, как можно оповещать пользователей о том, что их запрос не
относится ни к одному из тех классов, которые модель умеет определять.
Спасибо!

### Полезные материалы
● [Статья](https://aclanthology.org/2022.emnlp-industry.51/) про Out of Scope (OOS) detection.

● [Материал](https://arxiv.org/abs/2211.05561) об оценке меток для Out-of-Domain (OOD) интентов.

● [Ссылка](https://aclanthology.org/2022.emnlp-main.98/), содержащая информацию о системе обучения K-ближайших соседей для
обнаружения OOD интентов.
