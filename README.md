# JobLsnMsgDrvArhitec05

Используя весь опыт предыдущих уроков   
и код из методички воспроизвести приложение описанное в тексте материала;  
Настроить политики повторов и повторной доставки для всех потребителей;  
Реализовать тип Fault<T> для всех потребителей,   
добавить в сагу компенсационное действие -   
отмена предыдущих действий.   
Например, при ошибке в бронировании, нужно отозвать заказ на кухне].
Добавить в сервис Kitchen правило,   
что мы не принимаем предзаказ с типом Lasagna:   
добавить генерацию исключения,   
в сервисе бронирования реализовать каждый четвертый запрос  
на бронирование с Lasagna;
Включить Transaction Outbox для всех сервисов.   
Задание на отладку:   
добиться срабатывания работы паттерна Transaction Outbox   
реализованного в Mass Transit “наяву”, чтобы лучше усвоить его работу;
(*) Реализовать Transaction Outbox в базе данных.   
Заниматься вопросом работы при кластеризации и блокировке записей не нужно.