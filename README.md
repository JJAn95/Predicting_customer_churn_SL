# supervised_learning
ENG

In this educational project, I will utilize supervised machine learning (Supervised Learning) to predict customer churn in a bank.

In this educational project, I will use supervised machine learning techniques to predict customer churn in a bank. The goal of the project is to develop a model that, based on historical data, can forecast whether a customer will leave the bank or not. The provided data includes customer behavior and contract termination records. To predict customer churn, I will build a model with a high F1-score. By iterating through different algorithms, tuning hyperparameters, and addressing class imbalance, I aim to achieve an F1-score of at least 0.59. The performance of the model will be evaluated using a test dataset. Additionally, I will measure the AUC-ROC and compare it with the F1-score.

Action plan:

Data loading and preparation.<br>
Exploring class imbalance and training a model without considering the imbalance.<br>
Improving the model's performance by addressing class imbalance. Training different models and selecting the best one. Summarizing the findings.<br>
Conducting final testing.

Data description:

RowNumber: Index of the data row.<br>
CustomerId: Unique identifier of the customer.<br>
Surname: Customer's surname.<br>
CreditScore: Credit rating.<br>
Geography: Country of residence.<br>
Gender: Gender.<br>
Age: Age.<br>
Tenure: Number of years the customer has been with the bank.<br>
Balance: Account balance.<br>
NumOfProducts: Number of bank products used by the customer.<br>
HasCrCard: Whether the customer has a credit card.<br>
IsActiveMember: Customer's activity status.<br>
EstimatedSalary: Estimated salary.<br>

Target feature:

Exited: Customer churn status.

RUS

В этом учебном проекте я буду применять машинное обучение с учителем (Supervised Learning) для прогнозирования оттока клиентов банка.

Моделирование ситуации:

В Бета-Банке наблюдается отток клиентов, который происходит ежемесячно. Хотя это незначительное явление, оно оказывает заметное влияние. С целью минимизации затрат на привлечение новых клиентов, маркетологи банка решили сосредоточиться на удержании текущих клиентов. Для этого требуется прогнозировать, покинет ли клиент банк в ближайшее время или останется. У меня имеются исторические данные о поведении клиентов и расторжении договоров с банком. Для прогнозирования оттока клиентов я планирую построить модель с высоким значением F1-меры. С помощью перебора алгоритмов обучения, настройки гиперпараметров и балансировки классов, я стремлюсь достичь значения метрики не менее 0,59. Затем проверю F1-меру на тестовой выборке. Также буду измерять значение AUC-ROC и сравнивать его с F1-мерой.

План действий:

Загрузка и подготовка данных.<br>
Исследование баланса классов и обучение модели без учета дисбаланса.<br>
Улучшение качества модели с учетом дисбаланса классов. Обучение различных моделей и выбор наилучшей. Краткое описание выводов.<br>
Проведение финального тестирования.<br>

Описание данных:

RowNumber: индекс строки в данных.<br>
CustomerId: уникальный идентификатор клиента.<br>
Surname: фамилия.<br>
CreditScore: кредитный рейтинг.<br>
Geography: страна проживания.<br>
Gender: пол.<br>
Age: возраст.<br>
Tenure: количество лет, которое клиент является клиентом банка.<br>
Balance: баланс на счете.<br>
NumOfProducts: количество продуктов банка, используемых клиентом.<br>
HasCrCard: наличие кредитной карты.<br>
IsActiveMember: активность клиента.<br>
EstimatedSalary: предполагаемая зарплата.

Целевой признак:

Exited: факт ухода клиента.
