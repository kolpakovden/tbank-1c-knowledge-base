### Т‑Рассрочка
### Ман

1. [Подключение и идентификаторы `shopId`, `showcaseId`](connection.md)
2. [Расшифровка структуры `promoCode`](promo-code.md)
3. [Суммы `order_amount`, `credit_amount`, `transfer_amount`](amounts.md)
4. [Жизненный цикл заявки, `Info` и уведомления](lifecycle.md)
5. [Подключить новую точку](guides/add-location.md)
6. [Смена юридического лица: что перепроверить](guides/change-legal-entity.md)
7. [Сверить продажу, комиссию и фактическое поступление](guides/reconcile-amounts.md)

### Ошибки

[Все ошибки Т‑Рассрочки](errors/README.md): отсутствие доступных продуктов; `Authentication is required for Api`; неверная связка торговой точки; оплачено в банке, но не отражено в 1С; расхождение сумм.

Полезное правило: **создание ссылки ≠ подтверждение оплаты**, а корректная пара ID **не гарантирует** наличие нужного промокода и API-доступа.

### Официальная документация по теме

- [Обзор API Т‑Рассрочки](https://forma.tbank.ru/docs/online/setup-types/api/description-api)
- [Справочник терминов и промокодов](https://forma.tbank.ru/docs/online/)

[← Главная](../README.md) · [Общие правила диагностики](../docs/architecture-1c.md)
