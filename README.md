# Prod5_Dur4_Subscr_UT_ru

___Продуктовая / клиентская аналитика : пример.___

Синтетические данные с 5-ю продуктами, 4-мя длительностями подписки, 956-ю клиентами, историей подписок и использования за 728 дней.

2023.05.13. Начальная выкладка данных и
 - __Разведочная визуализация данных__
    - Все детали сразу
    - Падающая выручка и укорачивающаяся подписка
    - "Циклический" или "Сезонный"?
    - DAU и время пользования
    - Быстрый взгляд на клиентов
   
 - __Моделирование__
    - _Останется ли клиент на два года?_
        - Деревья решений
        - Histogram Gradient Boosting Classifier
    - _Сколько в точности будет оставаться клиент?_
        - Линейные модели не справились
        - Histogram Gradient Boosting Regressor не справился
        - Трюк: классификатор предсказывает число
