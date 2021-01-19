# DS-team-roadmap

![roadmap](files/roadmap.png)

#### Как мы проверяем и оцениваем гипотезы в YouDo, Адам Елдаров, Head of Product and Data Science
https://www.youtube.com/watch?v=jmjzSor1WDU
>Как организовать DS в компании, какие варианты построения команд есть, как фокусировать команду на самом важном, проверять гипотезы и как оценивать их эффективность для бизнеса.

## Организация кода
Система организации кода и связанной с ним технической части проекта.  
<img src="files/DS-maturity.png" alt="maturity" width="600" height="300">

### Типовая структура git репозитория
#### Описание
Структура репозитория для унификации, прозрачности работы и упрощения переключения между проектами для всех участников команды и сотрудников компании.

#### Ссылки
- [hitchhikers-guide by Data Science for Social Good](https://github.com/dssg/hitchhikers-guide/tree/master/sources/curriculum/0_before_you_start/pipelines-and-project-workflow)
- [The Data Science Lifecycle Process](https://github.com/dslp/dslp-repo-template)
- [cookiecutter-data-science by drivendata](https://github.com/drivendata/cookiecutter-data-science), [blog](https://drivendata.github.io/cookiecutter-data-science/)
- [GPN](https://github.com/gazprom-neft/standards/tree/master/template_project/template)

### Environment (requirements)
#### Описание
Управление зависимостями помогает управлять всеми библиотеками, необходимыми для работы приложения.
Можно как использовать виртуальное окружение (приоритетный вариант), так и работать с ноутбуками в контейнере.

#### Ссылки
>https://medium.com/python-pandemonium/better-python-dependency-and-package-management-b5d8ea29dff1

### Pep8
#### Описание
Единый стандарт написания кода для унификации стиля написания кода и упрощения чтения кода.
    
#### Ссылки
>https://pep8.org  
>https://gist.github.com/RichardBronosky/454964087739a449da04 - pep8 cheat sheet (short)

### Code review
#### Описание
Проверка исходного кода на ошибки, проблемы постановки эксперимента.

#### Ссылки
>https://tlroadmap.io/roles/technical-lead/product-quality/code-review.html
>https://mtlynch.io/human-code-reviews-1/
>https://mtlynch.io/human-code-reviews-2/
>https://youtu.be/2F6J82-Ch88

### Internal reporting (automized in Python)
#### Описание
Заполнение документов о результатах проверки гипотез, а также внутренние отчеты (по работе моделей и тд).
Процесс должен быть унифицирован и автоматизирован в начале или до начала очередного проекта.
    
#### Ссылки
>[Пример отчета](https://drive.google.com/file/d/1jahPaEie6T4hBrun4HkysXqibxntjkV_/view?usp=drivesdk)

### External reporting (semi-automized)
#### Описание
Внешний отчеты для заказчика/клиента/контролирующих органов. Могут составляться по гостам, по форме, согласованной до начала/в процессе проекта, в свободной форме.

#### Ссылки
>Пример отчета

## Роли в команде
Система организации команды.

<img src="files/team-customer-connection.png" alt="team-customer-connection" width="400" height="250">

### Дизайн команды
#### Описание
Актуально и для единой структурной единицы (лаборатории, отдела), и для проектной команды, работающей над одним бэклогом.
У каждой роли свой список обязанностей (должностная инструкция) и свой круг ответственности. 
Обязанности и ответственность могут меняться в зависимости от проекта и этапа проекта.

- Responsibility assignment matrix:
<img src="files/RACI.png" alt="RACI" width="700" height="300">
    
#### Ссылки
>https://tlroadmap.io/roles/people-manager/team-management/team-design.html

### AI Product owner
#### Описание
- Мост между бизнесом и DS.
- Понимание возможностей и ограничений DS.
- Полномочия принятия решений.
- Ответственность за результат с точки зрения бизнеса и потребителя.

#### Ссылки
    todo

### Project manager

### Team lead
#### Описание
Team lead - связь между продукт менеджером/продукт овнером и членами DS команды/команды разработки. 
Может совмещать роли продукт менеджера, проджект менеджера.
    
#### Ссылки
>Team lead roadmap – это карта навыков и компетенций тимлидов, которую можно адаптировать для любой компании и команды:  
>https://github.com/tlbootcamp/tlroadmap

### Data scientists

### Developers

## Управление проектом
Система организации проектной деятельности.

### Взаимодействие членов команды
#### Описание
Планируемые встречи (взаимодействие команды): 
- Брейнстормы - для наполнения бэклога и определения архитектуры решения (раз в 2 недели)
- Стендапы - для обеспечения прозрачности и выявления рисков/проблем (ежедневно, через день)
- Ретроспективы (ретро) - для настройки процесса и понимания слабых мест (раз в 2 недели)

#### Ссылки

### Организация проекта
#### Описание
Система, описывающая все процессы взаимодействия с внешними и внутренними лицами и исполнителями.
    
#### Ссылки
>[Team Data Science Process (TDSP)](https://docs.microsoft.com/ru-ru/azure/machine-learning/team-data-science-process/lifecycle-data)  
>https://youtu.be/HJML5Ghz-hk

### Организация канбан доски
#### Описание
Канбан доска создаётся на основе болей и проблем команды, чтобы она была вспомогательным инструментом в работе и в обеспечении качества проекта.
    
#### Ссылки
>https://www.youtube.com/watch?v=QYkuv2zuCFk

## Оценка продуктивности
Оценка личной и командной продуктивности. 
Процесс может быть выстроен как регулярный анализ и разбор метрик продуктивности (пример команды) или как регулярные performance review (пример члена команды).

### Individual
#### Описание
Оценка эффективности членов команды чаще всего проходит с помощью регулярных performance review. 
Performance review - это инструмент измерения эффективности члена команды.

Как часто:
- По времени (раз в квартал)
- По проектам (после каждого крупного проекта)

Дополнительно использовать one-on-one Тим Лида с каждым членом команды, чтобы рассказать результаты ревью, собрать обратную связь, а также обсудить вопросы, которые лучше не выносить на публику.

#### Ссылки
>[Performance review](https://youtu.be/HKXJ_AWPVBA)  
>[One-on-One 1](https://github.com/YKatser/DS-links/blob/master/TeamLeadLectures.md#георгий-могелашвили-bookingcom-эффективные-1-на-1)  
>[One-on-One 2](https://github.com/YKatser/DS-links/blob/master/TeamLeadLectures.md#встречи-one-on-one-инструмент-эффективного-управления-сотрудниками-никита-бакунин)

### Team
#### Описание
Оценка эффективности команды. Можно через ttm и другие продуктовые метрики.
    
#### Ссылки
>https://youtu.be/c0CRiCeJ99s
    

