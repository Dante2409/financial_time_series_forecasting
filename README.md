# Прогнозирование Финансовых Временных Рядов
## Описание проекта
Этот проект посвящен прогнозированию временных рядов цен акций Apple (AAPL) с использованием различных методов машинного обучения, включая ARIMA и LSTM сети на PyTorch. Проект основан на данных цен акций Apple, взятых с Yahoo Finance, охватывая период с 1990 по 2024 годы. Целью проекта является сравнение эффективности традиционных статистических моделей и современных методов глубокого обучения для прогнозирования временных рядов.

## Технические требования
Для запуска проекта вам потребуется Python и несколько дополнительных библиотек. Установите необходимые зависимости с помощью следующей команды:

```bash
pip install pandas numpy matplotlib statsmodels torch yfinance pmdarima
```

## Выводы по работе
- ARIMA модель: Результаты ARIMA модели оказались неудовлетворительными с отрицательным значением R², что указывает на неспособность модели адекватно предсказывать изменения цен акций.
- LSTM модель: Модель LSTM, разработанная с использованием PyTorch, продемонстрировала высокую точность прогнозирования, подтвержденную значениями коэффициента детерминации R², MAE и MSE.
- В ходе исследования подтвердилось, что методы глубокого обучения могут эффективно применяться для анализа и прогнозирования финансовых временных рядов, учитывая их сложную структуру и динамику.

## Acknowledgment
Код и подходы, использованные в этом проекте, были вдохновлены статьей с сайта [GeeksforGeeks](https://www.geeksforgeeks.org/time-series-forecasting-using-pytorch/).

## Авторы
- Ткаченко Елизавета Андреевна
- Хоменко Иван Михайлович
