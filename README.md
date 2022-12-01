# Neo4j 5 Logging examples

Neo4j5 ships with log4j2 as logging infrastructure : https://neo4j.com/docs/operations-manual/current/monitoring/logging/

This repository contains example of log4j configs to filter query logs based on criteria


- filter based on agent
- filter based on the authenticated user
- filter based on the content of a Cypher query
- filter based on the database name
- multiple log files for different databases
- filter based on source
- filter based on transaction event type
- filter based on transaction metadata