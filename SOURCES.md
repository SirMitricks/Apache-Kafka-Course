# Источники и статус проверки

### Источники

- Пакет `@confluentinc/kafka-javascript` (версия 1.11.0, на основе librdkafka 2.16.0, интерфейс `.KafkaJS`, нужен Node.js 18+): https://www.npmjs.com/package/@confluentinc/kafka-javascript
- Пакет `@confluentinc/schemaregistry` (1.11.0): https://www.npmjs.com/package/@confluentinc/schemaregistry
- Библиотека `avsc` (5.7.9) для Avro: https://www.npmjs.com/package/avsc
- Документация Apache Kafka: https://kafka.apache.org/documentation/
- Документация и список настроек librdkafka (параметры вроде `enable.idempotence`, `transactional.id` передаются клиенту как есть): https://github.com/confluentinc/librdkafka/blob/master/CONFIGURATION.md
- Остальные источники и глоссарий — в конце документа (раздел «Глоссарий и источники»).

Почему не KafkaJS: его последний релиз (2.2.4) вышел в феврале 2023 года. Интерфейс `.KafkaJS` в пакете Confluent создан похожим, поэтому старый код часто легко перенести.

