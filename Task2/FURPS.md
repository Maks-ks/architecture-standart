| Код | Требования                         | Комментарий  |
|-----|------------------------------------|--------------|
| F   | Функциональные (Functionality)     |              |
|     | Новый клиент видит на сайте список доступных депозитов с актуальными ставками                              |              |
|     | Клиент может оставить на сайте заявку на депозит, оставив телефонный номер и Ф.И.О.                                |              |
|     | В интернет-банке клиент видит список доступных депозитов с актуальными ставками и персонализированные ставки лично для него.                                   |              |
|     | В интернет-банке, указав счёт и сумму депозита, клиент может подать заявку на открытие депозита. Операцию открытия депозита необходимо подтверждать с помощью СМС-кода                               |              |
|     | В АБС необходимо реализовать функционал ведения ставок                                |              |
|     | В АБС необходимо реализовать функционал подтверждения условий депозита                               |              |
| U   | Удобство использования (Usability) |              |
|     | Интерфейс работы должен быть максимально удобным для клиента                                 |              |
|     |Необходимо придерживаться системы дизайна для приложений, которая принята в компании. Пользователи при работе должны видеть привычные цвета и брендированные элементы.                                |              |
| R   | Надёжность (Reliability)           |              |
|     | Все сервисы должны работать 24/7 и быть доступны в 99,9% случаев                                |              |
|     | В случае сбоев в ЦОД необходимо, чтобы сервисы интернет-банка были доступны и выдерживали требуемую нагрузку                               |              |
|     | Предусмотреть равномерное горизонтальное масштабирование и распределение запросов между серверами, приложениями и ЦОД                                |              |
| P   | Производительность (Performance)   |              |
|     | Отклик по всем операциям должен быть максимально быстрым и занимать миллисекунды                                |              |
| S   | Поддерживаемость (Supportability)  |              |
|     | Предусмотреть разработку документации                                |              |
| +R  | + Ограничения (Restricitions)      |              |
|     | С сайта и интернет-банка передается чувствительная информация, необходимо шифрование                                |              |
|     | При доработках предпочтительнее использовать технологии, которые уже есть в банке. Базы данных: MS SQL, Oracle. Бэкенд: .NET. Очереди: Kafka (на перспективу)                                 |              |
|     | Для реализации задачи открытия депозитов можно использовать микросервисную архитектуру                               |              |
|     | АБС и интернет банк реализованы на устаревающих технологиях, которые негативно могут сказаться на скорости внесения изменений/сопровождении, а также на масштабировании                                 |              |