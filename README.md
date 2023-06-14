# ExactusVectorIndex


Библиотека ExactusVectorIndex для распределенной индексации и поиска в сверхбольших массивах векторных представлений (эмбеддингов) с применением машинного обучения для преобразования векторных пространств и выборки данных.  


Состоит из двух репозиториев:
* [Клиентская часть](https://gitlab.com/vecindexer/vecindexerclient)
* [Серверная часть](https://gitlab.com/vecindexer/vecindexercpp)

### Перечень направлений прикладного использования


Библиотека позволяет создавать:

* распределенные системы мультимодального информационного поиска в больших массивах разноструктурированных данных (текстов, изображений, мультимедиа);

* рекомендательные системы.


Библиотека ExactusVectorIndex может применяться в этих системах для индексации, хранения и поиска по векторным представлениям, что позволяет выполнять следующие функции: поиск ответа на вопрос, поиск похожих векторов (ближайших соседей), анализ разнородных объектов (классификация, кластеризация). 

### Минимальные системные требования к аппаратным средствам для использования библиотеки

*	Процессор: архитектура: x86_64 ; количество ядер: 4; тактовая частота процессора 2 Ггц, не менее. 
*	Оперативная память 16 Гбайт, не менее. 
*	Дисковая подсистема объемом не менее 1000 Гбайт: скорость записи не менее 100 Мб/с, скорость чтения не менее 100 Мб/с. 
*	Операционная система: GNU/Linux Debian11 или совместимые. 
*	Версия Python: 3.9, не менее. 
*	Графический вычислитель (GPU): с объёмом оперативной памяти (видеопамяти) 8 Гбайт, не менее, совместимый с CUDA 11 (при хранении базы векторов в GPU).


Библиотека также может функционировать в облачной (виртуальной) инфраструктуре, характеристики которой соответствуют или превосходят указанные выше требования


### [Документация](https://exactusvectorindex.readthedocs.io/)


### Благодарности

Библиотека создана при поддержке Фонда содействия инновациям (Договор № 12ГУКодИИС12-D7/72692 о предоставлении гранта на выполнение проекта открытых библиотек от 27 декабря 2021 г).   
