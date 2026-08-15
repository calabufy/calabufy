<div align="center">

# Антон Александрович Щукин

### Junior Data Scientist / Machine Learning Engineer

Аналитика данных · Классическое машинное обучение

[GitHub](https://github.com/calabufy) · [Kaggle](https://www.kaggle.com/moonlittail) · [Telegram](https://t.me/AAShchukin_452b) · [Email](mailto:Antonovka2310@yandex.ru)

</div>

## Обо мне

Работаю с задачами прогнозирования временных рядов, детекции аномалий, бинарной и многоклассовой классификации. Умею формулировать гипотезы, выбирать метрики, строить baseline и аргументировать выбор подхода.

Имею опыт в глубоком обучении и Computer Vision, включая сегментацию и классификацию изображений. Окончил СПбГУАП с красным дипломом по направлению математического обеспечения информационных систем. Автор публикаций IEEE, индексируемых в Scopus, и ВАК.

Санкт-Петербург · Готов к удаленной работе

## Технологии

**Языки:** `Python`, `SQL`  
**Анализ данных:** `pandas`, `NumPy`, `EDA`, `статистический анализ`, `A/B-тесты`, `визуализация`  
**Машинное обучение:** `scikit-learn`, `CatBoost`, `Random Forest`, `SVM`, `Logistic Regression`, `AdaBoost`  
**Глубокое обучение:** `PyTorch`, `TensorFlow/Keras`, `CNN`, `RNN`, `LSTM`, `GRU`, `Autoencoder`, `U-Net`, `ConvLSTM`  
**Временные ряды:** `ARIMA`, `seasonal decomposition`, `anomaly detection`, `forecasting`  
**Метрики:** `MAE`, `MSE`, `RMSE`, `R²`, `Precision`, `Recall`, `F1`, `ROC-AUC`, `Dice`, `WoE`   
**Инструменты:** `Git`, `Jupyter Notebook`, `matplotlib`, `Docker`, `MLflow`, `PostgreSQL`, `pytest`

## Проектный опыт

**Data Scientist / ML Engineer - учебные и исследовательские проекты**  
2024 - настоящее время

## Избранные проекты

### 1. Кредитный скоринг

Прогнозирование серьезной просрочки клиента в течение 90 дней после выдачи займа по анкетным, транзакционным и кредитным данным.

- Провел EDA и анализ качества данных: пропуски, выбросы, корреляции, WoE и Information Value.
- Проверил признаки на потенциальную утечку целевой переменной.
- Сформировал агрегированные признаки по транзакциям, кредитному бюро и предыдущим займам.
- Реализовал отдельные пайплайны предобработки для линейных и нелинейных моделей.
- Сравнил Logistic Regression, SVC, SGDClassifier, Random Forest, LightGBM, XGBoost и CatBoost.
- Выполнил отбор признаков по IV и настройку CatBoost через RandomizedSearchCV.

**Результат:** ROC-AUC `0.83407`.

`Python` `pandas` `scikit-learn` `LightGBM` `XGBoost` `CatBoost` `WoE/IV` `RandomizedSearchCV` `Stratified K-Fold`

[GitHub Repository](https://github.com/calabufy/shift_test_23072026)

### 2. Детекция аномалий состояний оборудования

Бинарная классификация нормального и аварийного режимов работы по данным сенсоров космического корабля.

- Выполнил логарифмическое преобразование данных и анализ линейных комбинаций признаков.
- Реализовал генетический отбор около 100 признаков с оптимизацией по F1.
- Настроил гиперпараметры AdaBoost LSTM.
- Обучил автокодировщик на штатных данных и сравнил ансамблевый подход с детекцией аномалий через Autoencoder.

`LSTM` `Dense` `AdaBoost` `Autoencoder` `генетические алгоритмы` `Precision` `Recall` `F1`

[Kaggle Notebook](https://www.kaggle.com/code/moonlittail/adaboost-lstm-with-dense-layers-autoencoder)

### 3. Прогнозирование концентрации хлорофилла «а»

Прогнозирование временного ряда с сезонными составляющими на основе статистических и нейросетевых методов.

- Обработал выбросы и удалил сезонный тренд.
- Построил модели ARIMA и полиномиальной регрессии.
- Провел сравнительный анализ подходов по точности прогноза.

`ARIMA` `полиномиальная регрессия` `анализ временных рядов` `Python`

[Публикация в eLIBRARY.RU](https://www.elibrary.ru/item.asp?edn=gssocz)

### 4. Сегментация космических объектов

Дипломная работа по обнаружению и сегментации объектов на последовательностях астрономических кадров с учетом пространственно-временных признаков.

- Построил двухэтапную каскадную архитектуру: бинарная сегментация на основе U-Net и многоклассовая сегментация на основе U-Net + ConvLSTM.
- Настроил Tversky loss.
- Сравнил ML-методы классификации объектов.

`U-Net` `ConvLSTM` `Tversky loss` `ROC-AUC` `Precision` `Recall` `Dice` `Python`

[IEEE Xplore - Scopus](https://ieeexplore.ieee.org/document/11049979) · [Бинарная сегментация](https://www.kaggle.com/code/moonlittail/space-object-segmentation-model-1) · [U-Net + ConvLSTM](https://www.kaggle.com/code/moonlittail/space-objects-segmentation-model-2-convlstm)

## Публикации и исследования

- **Сегментация космических объектов на астрономических изображениях** - [IEEE Xplore, Scopus](https://ieeexplore.ieee.org/document/11049979)
- **Прогнозирование концентрации хлорофилла «а»** - [eLIBRARY.RU, ВАК](https://www.elibrary.ru/item.asp?edn=gssocz)

## Образование

- **Национальный исследовательский университет ИТМО**
  Магистратура, 01.04.02 «Искусственный интеллект и поведенческая экономика»
  2026-2028


- **Санкт-Петербургский государственный университет аэрокосмического приборостроения - СПбГУАП**
  Бакалавриат, 02.03.03 «Математическое обеспечение и администрирование информационных систем»
  Диплом с отличием · Средний балл: `4.83`, 2022-2026

## Контакты

- Email: [Antonovka2310@yandex.ru](mailto:Antonovka2310@yandex.ru)
- Telegram: [@AAShchukin_452b](https://t.me/AAShchukin_452b)
- GitHub: [calabufy](https://github.com/calabufy)
- Kaggle: [moonlittail](https://www.kaggle.com/moonlittail)
