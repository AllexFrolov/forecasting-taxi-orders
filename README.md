# forecasting-taxi-orders
Задача: Обучить модель для предсказания количества заказов такси на следующий час. В качестве данных выступает история заказов такси в аэропортах. Интервал между записями 10 минут.
* Данные преобразованы к часовому периоду. Проверены на отсутствие пропусков и аномальных значений.
* Проведена декомпозиция временного ряда, выведены графики трендов и сезонностей. Замечен растущий долгосрочный тренд. Также выделены междневные сезоны.
* Для лучшей работы модели, были добавлены новые признаки, а именно скользящее среднее и значения с предыдущих периодов.
* Были выбраны несколько моделей: Линейная регрессия, граиентный бустинг, случайны лес.
* Представены графики предсказаний натренированных моделей, а также диаграммы значимости признаков
* В качестве итоговой модели по значению целевой метрики RMSE была выбрана и протестирована модель градиентного бустинга.

Стек: Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn
