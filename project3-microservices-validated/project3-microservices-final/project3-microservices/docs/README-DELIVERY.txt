Состав проекта:
- README.md — отчёт на русском языке, шаги 1–4, сервисы, ПО, сценарии и взаимодействия.
- docs/architecture.drawio — исходник архитектурной схемы, открывается на https://app.diagrams.net/
- docs/architecture.png — экспорт архитектурной схемы.
- docs/sequence-success.png — успешный сценарий.
- docs/sequence-failure.png — сценарий сбоя с компенсацией.
- api/*.yaml — пять спецификаций OpenAPI, по одной на бизнес-сервис.
- events/event-schemas.yaml — общая оболочка и перечень событий RabbitMQ.

Перед сдачей рекомендуется проверить YAML в Swagger Editor и Redocly CLI, а также загрузить каталог в свой Git-репозиторий.
