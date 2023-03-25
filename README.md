# Neo4j 5 Logging examples

Neo4j5 ships with log4j2 as logging infrastructure : https://neo4j.com/docs/operations-manual/current/monitoring/logging/

This repository contains example of log4j configs to filter query logs based on criteria


- filter based on agent [agent-filter](./agent-filter/)
- filter based on the authenticated user [authenticated-user-filter](./authenticated-user-filter/)
- filter based on the content of a Cypher query [composite-filters](./composite-filters/)
- filter based on the database name [cypher-query-filter](./cypher-query-filter/)
- multiple log files for different databases [query-file-per-db](./querylog-file-per-db/)
- filter based on source [source-filter](./source-filter/)
- filter based on transaction event type [tx-event-filter](./tx-event-filter/)
- filter based on transaction metadata [tx-metadata-filter](./tx-metadata-filter/)
- using JsonTemplateLayout [json-layout](./json-layout/)
- query logs to console out [logs-to-console](./logs-to-console/)