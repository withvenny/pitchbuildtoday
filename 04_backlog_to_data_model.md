# 04. Backlog to Data Model

## Purpose

This step converts a structured backlog into a data model.

The goal is to identify the information the product needs to store, relate, validate, update, protect, and make available to later system layers.

## Accepted Inputs

The agent may ingest the backlog from the previous step, along with actor, verb, noun patterns, scenarios, priorities, dependencies, permissions, workflow notes, business rules, and acceptance expectations.

The input should provide enough behavioral clarity for the agent to identify data objects and relationships.

## Transformation

The agent is responsible for extracting the data model implied by the backlog.

The agent should identify entities, fields, relationships, statuses, enums, ownership rules, permissions, timestamps, logs, and validation needs without locking the product into a specific database vendor too early.

## Output

The output is a data model that gives the next step enough context to design an API.

The data model should help a reader understand what objects exist, how they relate, what states they move through, and what rules govern their use.

## Output Format

The preferred output is a schema-ready artifact that can be saved as `.yaml`, `.yml`, `.json`, `.md`, or another format suitable for review and handoff.

The format should remain clear enough to support future database, API, and application decisions.

## Gate

This step is complete when the product’s major data objects, relationships, fields, statuses, ownership rules, and validation needs can be understood without revisiting the backlog.

The next step should not have to guess what resources the API will need to expose.

## Agent

Use the related agent to transform the backlog into a data model.

[Download or open the Backlog to Data Model Agent](./agents/04_backlog_to_data_model_agent.md)

## Next Step

After the data model is created, continue to the API step.

[Continue to Data Model to API](./05_data_model_to_api.md)

🌋
