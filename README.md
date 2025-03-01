<center><h1>Методы Монте-Карло и машинное обучение</h1></center>

## Прериквизиты

- **Программирование на Python.** Уверенное владение основами Python, включая умение писать и понимать код, а также работать с основными библиотеками для численных вычислений и анализа данных, такими как NumPy, Pandas, Seaborn и Matplotlib.
- **Анализ и визуализация данных.** Опыт работы с данными, включающий их сбор, предобработку, визуализацию и анализ с использованием инструментов Python. Понимание методов очистки, нормализации и аугментации данных.
- **Основы статистики и теории вероятностей.** Знание ключевых концепций статистики, таких как вероятностные распределения, математическое ожидание и дисперсия. Опыт работы с вероятностными моделями, включая базовые байесовские методы.
- **Линейная алгебра.** Базовое понимание линейной алгебры, включая операции с матрицами и векторами, а также их применение в машинном обучении, например, при работе с нейросетями.
- **Вероятностное моделирование.** Знакомство с основами вероятностного моделирования, включая априорные и апостериорные распределения, а также базовые навыки работы с байесовскими методами.
- **Машинное обучение.** Понимание основных алгоритмов машинного обучения, таких как регрессия, классификация и кластеризация, а также базовые знания в области глубокого обучения и архитектуры нейросетей.
- **Работа с библиотеками для глубокого обучения.** Опыт работы с такими библиотеками, как PyTorch, для создания и обучения нейросетевых моделей.
- **Основы обработки сигналов.** Понимание цифровой обработки сигналов, включая дискретизацию и фильтрацию, а также знание методов улучшения и анализа звуковых сигналов.

## Темы лекций и семинаров

### Лекции

1. [**Введение в методы Монте-Карло.**](https://github.com/DmitryRyumin/HSE_Monte_Carlo_and_ML_2025/blob/main/tutorials/1.ipynb) Основы методов Монте-Карло, история их развития и их важность в контексте машинного обучения. Рассмотрение базовых понятий, таких как случайные процессы и моделирование неопределенности, а также их связь с задачами численного интегрирования и оценки вероятностных распределений. Практическое применение PyTorch для генерации случайных чисел и моделирования неопределенности в предсказаниях моделей.
2. [**Основы случайного моделирования.**](https://github.com/DmitryRyumin/HSE_Monte_Carlo_and_ML_2025/blob/main/tutorials/1.ipynb) Принципы случайного моделирования с использованием PyTorch. Рассмотрение различных типов распределений, таких как нормальное, Бернулли, экспоненциальное, и их применение в обучении моделей. Примеры использования сэмплирования для повышения эффективности методов Монте-Карло.
3. [**Методы Монте-Карло для интеграции и оценки.**](https://github.com/DmitryRyumin/HSE_Monte_Carlo_and_ML_2025/blob/main/tutorials/2.ipynb) Применение методов Монте-Карло для численного интегрирования, оценки функции правдоподобия и байесовских методов. Рассмотрение применения этих методов для задач регрессии, классификации и оценки доверительных интервалов. Акцент на использовании Монте-Карло для улучшения вероятностных моделей.
4. [**Марковские цепи Монте-Карло.**](https://github.com/DmitryRyumin/HSE_Monte_Carlo_and_ML_2025/blob/main/tutorials/3.ipynb) Алгоритмы Метрополис-Хастингса и Гиббса, их применение в байесовской оптимизации и апостериорном анализе. Примеры использования Марковских цепей Монте-Карло для генерации выборок из сложных распределений и моделирования неопределенности.
5. [**Монте-Карло в задачах обработки естественного языка (NLP).**](https://github.com/DmitryRyumin/HSE_Monte_Carlo_and_ML_2025/blob/main/tutorials/4.ipynb) Применение методов Монте-Карло для оценки неопределенности в задачах NLP, включая модели трансформеров, такие как BERT. Особое внимание уделяется задачам классификации текстов и распознаванию именованных сущностей (NER).
6. [**Монте-Карло для улучшения речи (Speech Enhancement).**](https://github.com/DmitryRyumin/HSE_Monte_Carlo_and_ML_2025/blob/main/tutorials/5.ipynb) Применение методов Монте-Карло для оценки и оптимизации моделей улучшения речи, таких как MP-SENet. Обсуждение методов повышения качества звука и анализа ошибок с использованием Монте-Карло.
7. **Методы Монте-Карло в компьютерном зрении (CV).** Применение методов Монте-Карло для оценки неопределенности в задачах классификации изображений. Использование библиотек Timm и Vit-Pytorch для работы с современными архитектурами нейросетевых моделей CV.
8. **Оптимизация гиперпараметров с использованием Монте-Карло.** Применение методов Монте-Карло для стохастической оптимизации гиперпараметров, включая имитацию отжига и байесовскую оптимизацию. Акцент на настройке моделей машинного обучения для повышения их производительности.
9. **Мультимодальные данные и методы Монте-Карло.** Применение методов Монте-Карло для работы с мультимодальными данными, такими как текст и изображения. Использование моделей CLIP и оценка неопределенности в задачах интеграции разнородных данных.
10. **Мультизадачные модели и методы Монте-Карло.** Применение методов Монте-Карло для оценки неопределенности и повышения производительности в многозадачных моделях. Примеры реализации многозадачных моделей в NLP и CV.
11. **Методы Монте-Карло для предсказания и прогнозирования.** Применение методов Монте-Карло для задач прогнозирования, таких как временные ряды и последовательности.
12. **Методы Монте-Карло в больших данных.** Масштабирование методов Монте-Карло для работы с большими объемами данных (корпусами). Использование PyTorch и других библиотек для управления большими нейросетевыми моделями и данными.
13. **Применение Монте-Карло в индустрии.** Реальные примеры использования методов Монте-Карло в промышленности, включая задачи NLP, речевых технологий и компьютерного зрения. Обзор тенденций и научных исследований в этой области.
14. **Заключение курса.** Обзор всех пройденных тем и итоговое обсуждение курса. Акцент на интеграции методов Монте-Карло в современные подходы к машинному обучению и обсуждение перспектив дальнейших исследований.

### Семинары

1. [**Введение и настройка окружения.**](https://github.com/DmitryRyumin/HSE_Monte_Carlo_and_ML_2025/blob/main/tutorials/1.ipynb) Установка и настройка окружения, включая PyTorch, TorchAudio и другие библиотеки. Введение в Jupyter Lab и базовая работа с генерацией случайных чисел и моделированием распределений.
2. [**Генерация случайных чисел и моделирование распределений.**](https://github.com/DmitryRyumin/HSE_Monte_Carlo_and_ML_2025/blob/main/tutorials/1.ipynb) Практическая работа с моделированием различных распределений и сэмплированием. Визуализация и анализ данных, полученных с помощью случайного моделирования.
3. [**Применение Монте-Карло для интеграции.**](https://github.com/DmitryRyumin/HSE_Monte_Carlo_and_ML_2025/blob/main/tutorials/2.ipynb) Реализация численных методов интеграции с помощью Монте-Карло, решение задач по оценке интегралов и математических ожиданий.
4. [**Марковские цепи и их реализация.**](https://github.com/DmitryRyumin/HSE_Monte_Carlo_and_ML_2025/blob/main/tutorials/3.ipynb) Реализация и оптимизация алгоритмов Марковских цепей Монте-Карло с использованием PyTorch. Практические задания по моделированию сложных распределений и оценке параметров моделей.
5. [**Монте-Карло для задач обработки естественного языка (NLP).**](https://github.com/DmitryRyumin/HSE_Monte_Carlo_and_ML_2025/blob/main/tutorials/4.ipynb) Работа с моделями трансформеров из библиотеки Hugging Face. Практические задания по оценке вероятностей и улучшению качества текстовых моделей с использованием методов Монте-Карло.
6. [**Монте-Карло для улучшения речи (Speech Enhancement).**](https://github.com/DmitryRyumin/HSE_Monte_Carlo_and_ML_2025/blob/main/tutorials/5.ipynb) Практическая работа с моделями улучшения речи и оценка их производительности с помощью методов Монте-Карло.
7. **Монте-Карло для компьютерного зрения (CV).** Практические задания по классификации изображений и улучшению качества предсказаний с использованием методов Монте-Карло.
8. **Оптимизация и оценка гиперпараметров.** Практическая оптимизация гиперпараметров моделей для задач NLP и CV. Оценка производительности моделей и применение стохастической оптимизации.
9. **Объединение данных из разных модальностей.** Разработка мультимодальных моделей и оценка их производительности с использованием методов Монте-Карло. Практические задания по объединению данных из различных источников.
10. **Монте-Карло для мультизадачности.** Практическая работа с многозадачными моделями и их оптимизация с использованием методов Монте-Карло.
11. **Монте-Карло для предсказания и прогнозирования.** Реализация моделей для прогнозирования и анализ предсказаний с использованием методов Монте-Карло.
12. **Применение Монте-Карло в задачах обработки больших данных.** Практическая работа с крупными наборами данных (корпусами) и оптимизация вычислений с помощью методов Монте-Карло.
13. **Проектное задание: часть 1 (подготовка данных и начальный анализ).** Сбор и предварительная обработка данных, включая очистку и анализ.
14. **Проектное задание: часть 2 (разработка и интеграция методов Монте-Карло).** Разработка и интеграция методов Монте-Карло в модели. Оптимизация моделей на основе данных, использование библиотеки PyTorch и других инструментов для работы с текстами, речью или изображениями, в зависимости от выбранной модальности.
15. **Проектное задание: часть 3 (оптимизация и оценка моделей).** Дальнейшая оптимизация моделей, улучшение точности предсказаний с использованием методов Монте-Карло, включая стохастическую оптимизацию и оценку доверительных интервалов. Подготовка промежуточных результатов и их обсуждение в группе для получения обратной связи и корректировки работы.
16. **Проектное задание: часть 4 (подготовка к защите проекта).** Завершение работы над моделями, финальная оптимизация и подготовка проекта к защите. Создание презентации и отчета, описывающего процесс разработки, результаты и выводы.
17. **Защита проектов.** Финальный семинар, посвященный защите проектов. Представление результатов, обсуждение процесса разработки и демонстрация применения методов Монте-Карло. Проведение анализа результатов и формирование заключений по каждому проекту.

## Система оценивания

Оценка за курс формируется следующим образом:
Оценка = 0.5 * Домашняя работа + 0.5 * Экзамен (итоговый проект)

### Домашняя работа

Всего предусмотрено **8** домашних заданий, каждое из которых оценивается в **0.5** балла. Задания охватывают различные аспекты применения методов Монте-Карло в задачах обработки естественного языка (NLP), речевых технологий (Speech/Signal Processing) и компьютерного зрения (CV).

Все домашние работы должны быть загружены на **GitHub**, и необходимо отправить ссылку на репозиторий в https://telegram.me/dmitry_ryumin

#### Критерии оценки для домашней работы

- Отлично (8) Выполненная домашняя работа
- Хорошо (6-7) Работа выполнена на 80%
- Удовлетворительно (4-5) Работа выполнена на 50%
- Неудовлетворительно (0-3) Работа выполнена менее чем на 50%

## Экзамен

Для сдачи экзамена по данному курсу необходимо подготовить учебный исследовательский проект. Проект должен быть основан на реальных данных, которые можно взять из открытых источников (например из https://huggingface.co/datasets). В рамках проекта студенты должны провести анализ данных, сформулировать задачу, обучить несколько моделей, выбрать наилучшую и обосновать свой выбор.

Экзамен включает презентацию работы, которая состоит из следующих частей:
- **Цель работы.** Четкое описание задачи, которую предстоит решить с использованием методов Монте-Карло.
- **Описание исходных данных.** Подробное представление данных, включая источник, структуру и ключевые характеристики.
- **Используемые алгоритмы с обоснованием.** Описание применяемых методов Монте-Карло и алгоритмов машинного обучения с объяснением, почему они были выбраны для решения задачи.
- **Как измерялось качество моделей.** Описание метрик, использованных для оценки производительности моделей, и методов анализа результатов.
- **Итоговые результаты.** Представление полученных результатов, выводы по сравнению моделей, а также их интерпретация.

На презентацию выделяется 10 минут (5 минут на доклад и 5 минут на вопросы). Допускается выполнение проекта в парах.
Весь код и презентация проекта должны быть загружены на **GitHub**, оформлены с **README файлом**, и необходимо отправить приглашение на репозиторий пользователю **DmitryRyumin**.

Критерии выставления оценок:
- 4 балла можно получить за выполнение домашних заданий (8 заданий по 0.5 балла за каждое, округление в пользу студента; для получения максимума необходимо выполнить все 8 заданий).
- 4 балла можно получить за защиту итогового проекта.
- 2 балла можно получить за выполнение дополнительных требований к проекту (1 балл за каждое):
    - Использование двух и более наборов данных (корпусов) из открытых источников, таких как Hugging Face Datasets.
    - Создание приложения с использованием Gradio, размещенного на Hugging Face, которое позволяет вводить данные для модели и получать результаты.
