# Портфолио Матвея Саева
Добро пожаловать в моё портфолио!  
Здесь собраны проекты в области анализа данных, машинного обучения и бизнес-аналитики с моделированием бизнес-процессов от крупных компаний.  

## 📌 Проекты
### 1) Pet-проекты:
- **Модель линейной регрессии прогнозирования цен на автомобили**:
*Описание:*
В этом проекте я применил линейную регрессию на практике, сделав попытку в предсказании стоимости машин и в определении, от каких факторов зависит ценообразование на автомобили. Помимо этого я выявил, какие переменные важны для прогнозирования и насколько хорошо полученная модель описывает данные.

*Ссылка на код и датасет:* [код](https://github.com/Theawtm/theawtm.github.io/blob/main/Pet-проекты%20(Аналитика)/Линейная%20регрессия%20прогнозирования%20цен%20на%20автомобили/Lin_Reg_Cars.ipynb) + [датасет](https://github.com/Theawtm/theawtm.github.io/blob/main/Pet-проекты%20(Аналитика)/Линейная%20регрессия%20прогнозирования%20цен%20на%20автомобили/cars.csv)

*Использованные инструменты:* sklearn, pandas, numpy, matplotlib, seaborn
- **A/B-тестирование новой системы доставки пиццы по пути от компании доставки еды**:
*Описание:* Рассматривается крупная компания по доставке пиццы с приложением для курьеров. В компании есть несколько ресторанов в разных частях города и целый штат курьеров. Но есть одна проблема — к вечеру скорость доставки падает из-за того, что курьеры уходят домой после рабочего дня, а количество заказов лишь растет. Это приводит к тому, что в момент пересмены наша доставка очень сильно проседает в эффективности. Data scientist-ы придумали новый алгоритм, который позволяет курьерам запланировать свои последние заказы перед окончанием рабочего дня так, чтобы их маршрут доставки совпадал с маршрутом до дома. То есть, чтобы курьеры доставляли последние свои заказы за день как бы "по пути" домой. Необходимо раскатить A/B тест на две равные группы курьеров. Часть курьеров использует старый алгоритм без опции "по пути", другие видят в своем приложении эту опцию и могут ее выбрать. Задача – проанализировать данные эксперимента и помочь бизнесу принять решение о раскатке новой фичи на всех курьеров.

	order_id - id заказа

	delivery_time - время доставки в минутах

	district - район доставки

	experiment_group - экспериментальная группа


*Ссылка на код и датасет:* [код](https://github.com/Theawtm/theawtm.github.io/blob/main/Pet-проекты%20(Аналитика)/AB%20тестирование%20доставка%20пиццы/TTests.ipynb) + [датасет](https://github.com/Theawtm/theawtm.github.io/blob/main/Pet-проекты%20(Аналитика)/AB%20тестирование%20доставка%20пиццы/experiment_lesson_4.csv)

*Использованные инструменты:* scipy.stats, pandas, numpy, matplotlib, seaborn, pingouin

- **A/B-тестирование нового формата изображений блюд и новой кнопки заказа для сервиса доставки готовых продуктов**:

Описание данных:

**5_task_1:**

	id – id клиента в эксперименте

	group – в каком разрешении показывались картинки (A – прямоугольные 16:9, B – квадратные, C – прямоугольные 12:4)

	events – сколько блюд суммарно было заказано за период

**5_task_2:**

	id – id клиента в эксперименте

	segment – сегмент (high/low)

	group – вид кнопки (control – старая версия, test – новая версия)

	events – сколько блюд суммарно было заказано за период

*Ссылка на код и датасет:* [код](https://github.com/Theawtm/theawtm.github.io/blob/main/Pet-проекты%20(Аналитика)/AB-тестирование%20доставка%20готовых%20продуктов/Delivery.ipynb) + [датасет 1 тест](https://github.com/Theawtm/theawtm.github.io/blob/main/Pet-проекты%20(Аналитика)/AB-тестирование%20доставка%20готовых%20продуктов/5_task_1.csv) + [датасет 2 тест](https://github.com/Theawtm/theawtm.github.io/blob/main/Pet-проекты%20(Аналитика)/AB-тестирование%20доставка%20готовых%20продуктов/5_task_2.csv)

*Использованные инструменты:* scipy.stats, pandas, numpy, matplotlib, seaborn

### 2) Проект "Т-Семья" в рамках обучения в Финтех на направлении "Бизнес-аналитика":

[Miro](https://miro.com/app/board/uXjVLq1AJYw=/)

[Прототипы](https://www.figma.com/design/CRPhELKKcaoYmRPJ95PmoZ/Untitled?node-id=0-1&t=j2gN5HoYjzKa4dJ4-1)

### 3) Курсовые проекты-кейсы от компаний:
- **Комплексный анализ бизнес-процессов архитектурной компании Геопроект и моделирование процесса разработки коммерческого предложения**:
*Использованные инструменты:* PESTEL-анализ, 5 сил М. Портера, КФУ, Первичный SWOT-анализ, Поэлементный SWOT-анализ, BPMN (AS IS и TO BE), SIPOC (AS IS и TO BE), RASCI (AS IS и TO BE), Дерево Исикавы, Дерево целей
- **SWOT-анализ группы компании Askona Life Group медицинского направления "Первый клинический медицинский центр"**:
*Использованные инструменты:* PESTEL-анализ, 5 сил М. Портера, КФУ, Первичный SWOT-анализ, Поэлементный SWOT-анализ
- **Комплексный анализ бизнес-процессов кейтеринговой компании "ООО СетФуршет" и моделирование процесса разработки и запуска маркетинговой кампании**:
*Использованные инструменты:* PESTEL-анализ, 5 сил М. Портера, КФУ, Первичный SWOT-анализ, Поэлементный SWOT-анализ, BPMN (AS IS и TO BE), SIPOC (AS IS и TO BE), RASCI (AS IS и TO BE), Дерево Исикавы, Дерево целей
### 4) Личный проект "Сервис поиска культурных мест и атрибутов для релокантов" в рамках майнора UX-дизайн:
*Использованные инструменты:* Кабинетные интервью, количественные исследования, Аффинити-диаграмма, User story map (пользовательские требования) + приоритизация по MoSCoW, CJM, Figma, Miro

*Дополнительные ссылки:* [User Story Map](https://miro.com/app/board/uXjVIQUzfUA=/), [Affinity Diagramm](https://miro.com/app/board/uXjVLEUuitc=/)
### 5) Проекты в рамках дисциплины "Интеллектуальный анализ данных":
- **Практическое использование библиотеки Numpy**:
*Ссылка на код:* [код](https://github.com/Theawtm/theawtm.github.io/blob/main/ИАД/Numpy%20(1).ipynb)

*Использованные инструменты:* numpy
- **Практическое использование библиотеки Pandas**:
*Ссылка на код и датасет:* [код](https://github.com/Theawtm/theawtm.github.io/blob/main/ИАД/Работа%20с%20Pandas/Pandas%20(2).ipynb) + [датасет](https://github.com/Theawtm/theawtm.github.io/blob/main/ИАД/Работа%20с%20Pandas/data.csv)

*Использованные инструменты:* pandas, numpy, matplotlib, seaborn
- **Визуализация данных с помощью seaborn и matplotlib и написание модели прогнозирования положения тела человека на основе признаков с датчиков**:
*Ссылка на код и датасет:* [код](https://github.com/Theawtm/theawtm.github.io/blob/main/ИАД/Визуализация%20и%20модель%20прогнозирования%20положения%20тела/Visualisations%20%2B%20predict%20(3).ipynb) + [датасет test](https://github.com/Theawtm/theawtm.github.io/blob/main/ИАД/Визуализация%20и%20модель%20прогнозирования%20положения%20тела/test.csv) + [датасет train](https://github.com/Theawtm/theawtm.github.io/blob/main/ИАД/Визуализация%20и%20модель%20прогнозирования%20положения%20тела/train.csv)

*Использованные инструменты:* sklearn, pandas, numpy, matplotlib, seaborn
- **KNN-классификация пингвинов по признакам и модель линейной регрессии для определения стоимости алмаза по основным характеристикам (размер, чистота, цвет и др.)**:
*Ссылка на код и датасет:* [код](https://github.com/Theawtm/theawtm.github.io/blob/main/ИАД/Линейная%20регрессия%20и%20KNN/KNN%20и%20Линейная%20регрессия%20(4).ipynb) + [датасет пингвины](https://github.com/Theawtm/theawtm.github.io/blob/main/ИАД/Линейная%20регрессия%20и%20KNN/penguins_data.csv) + [датасет бриллианты](https://github.com/Theawtm/theawtm.github.io/blob/main/ИАД/Линейная%20регрессия%20и%20KNN/diamonds.csv)

*Использованные инструменты:* sklearn, pandas, numpy, matplotlib, seaborn

## 📫 Контакты

📧 Email: mssaev@edu.hse.ru 

💼 Telegram: @Theawtm
