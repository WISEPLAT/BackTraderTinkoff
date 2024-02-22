# BackTraderTinkoff
Провайдер для автоторговли в [BackTrader](https://backtrader.com/) из [Tinkoff Invest API](https://tinkoff.github.io/investAPI/). Использует библиотеку [TinkoffPy](https://github.com/cia76/TinkoffPy). Для получения новых бар по расписанию потребуется библиотека [MarketPy](https://github.com/cia76/MarketPy).

### Для чего нужен
Чтобы торговые системы, написанные для BackTrader, можно было поставить на автоматическую торговлю с брокером Тинькофф Инвестиции.

### Установка провайдера
1. Скопируйте файлы проекта в папку с торговой системой BackTrader

### Начало работы
В папке **Examples** находится хорошо документированный код примера **LimitCancel.py**. В нем подробно объяснены:
1. Формат обращения к тикерам, в т.ч. фьючерсам
2. Настройка Cerebro без отображения статистики и получения событий без задержек
3. Включение системы ведения логов с выводом на консоль и в файл
4. Конфигурация брокера Алор
5. Конфигурация исторических и новых бар Алор
6. Размер позиции для акций и фьючерсов
7. Торговая система с параметрами
8. Обработка получения нового бара
9. Обработака статуса торговли
10. Обработка исполнения заявки
11. Обработка изменения статуса позиции

### Авторство, право использования, развитие
Автор данной библиотеки Чечет Игорь Александрович.

Библиотека написана в рамках проекта [Финансовая Лаборатория](https://finlab.vip/) и предоставляется бесплатно. При распространении ссылка на автора и проект обязательны.

Исправление ошибок, доработка и развитие библиотеки осуществляется автором и сообществом проекта [Финансовая Лаборатория](https://finlab.vip/).
### Что дальше
- Бесплатный курс "Автоторговля" по идеям, концепциям и процессам алгоритмической/автоматической торговли [смотрите здесь >>>](https://finlab.vip/wpm-category/autotrading2021/)


- Бесплатный курс "BackTrader: Быстрый старт" [ждет вас здесь >>>](https://finlab.vip/wpm-category/btquikstart/)


- [Подписывайтесь на Telegram канал "Финансовой Лаборатории",](https://t.me/finlabvip) чтобы быть в курсе всех новинок алгоритмической и автоматической торговли.