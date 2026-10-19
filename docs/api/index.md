# Документация API

API предоставляет доступ к функциям ИИ-сервиса.

## Основные операции

- `POST /classifications` — выполнить классификацию;
- `GET /classifications/{id}` — получить результат классификации;
- `PATCH /classifications/{id}` — провалидировать результат классификации.

## Спецификация

Описание API находится в файле <a href="openapi.yaml">`openapi.yaml`</a>, либо в интеграции Swagger ниже.

<swagger-ui src="openapi.yaml"/>
