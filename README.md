# order-events

Order acceptance, cancellation and shipment event contracts with inline Avro and JSON Schema.

`specification.yaml` is the authoritative, self-contained AsyncAPI document.
The System provisions validation, temporary schema extraction, Apicurio publication,
and Microcks import. Never commit generated schemas. Main commits publish by commit
SHA; normal release tags retain the existing contract release convention.

Registry group: `io.github.contractfirstkafka.demo.orderfulfillment`. Contract artifact: `order-events`.
Payload IDs and serializer configuration are described in the platform AsyncAPI guide.
