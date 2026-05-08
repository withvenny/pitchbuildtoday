# 05. Data Model to API

## Purpose

This step converts a data model into an API design package.

The goal is to define how the product’s data can be created, read, updated, deleted, filtered, protected, and exposed to future system layers.

## Accepted Inputs

The agent may ingest the data model from the previous step, along with entities, fields, relationships, statuses, enums, ownership rules, permissions, validation rules, logs, and unresolved schema questions.

The input should provide enough structural clarity for the agent to identify API resources, operations, request objects, response objects, and access rules.

## Transformation

The agent is responsible for converting the data model into an API design package.

The agent should identify resources, endpoints, methods, authentication needs, authorization rules, request and response patterns, pagination, filtering, sorting, errors, and integration considerations.

## Output

The output is an API design package that gives the next step enough context to create a CMS plan.

The API design should help a reader understand what resources exist, how those resources are accessed, what rules control them, and how other layers should communicate with the system.

## Output Format

The preferred output may be saved as `.md`, `.yaml`, `.json`, `.php`, or another format suitable for review, documentation, and implementation.

The format should remain clear enough to support future CMS, UI, web app, and integration work.

## Gate

This step is complete when the product’s major API resources, operations, access rules, request patterns, response patterns, and error expectations can be understood without revisiting the data model.

The next step should not have to guess how the CMS will communicate with the underlying system.

## Agent

Use the related agent to transform the data model into an API design package.

[Download or open the Data Model to API Agent](./agents/05_data_model_to_api_agent.md)

## Next Step

After the API design package is created, continue to the CMS step.

[Continue to API to CMS](./06_api_to_cms.md)

🌋
