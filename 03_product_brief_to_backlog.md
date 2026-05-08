# 03. Product Brief to Backlog

## Purpose

This step converts a product brief into a structured backlog.

The goal is to turn product direction into usable planning material that can support data modeling, workflow design, implementation planning, and future build decisions.

## Accepted Inputs

The agent may ingest the product brief from the previous step, along with supporting notes, assumptions, user definitions, product boundaries, success signals, constraints, and open questions.

The input should provide enough product clarity for the agent to identify what users need to do and what the system may need to support.

## Transformation

The agent is responsible for converting the product brief into a backlog that describes user behavior, product capabilities, workflow needs, and early acceptance expectations.

The backlog should organize the product into clear actor, verb, and noun patterns where possible so the next step can extract data objects, relationships, permissions, and system states.

## Output

The output is a structured backlog that gives the next step enough context to create a data model.

The backlog should help a reader understand the major users, actions, objects, priorities, dependencies, and expected outcomes of the product.

## Output Format

The preferred output is a structured backlog that can be saved as `.csv`, `.md`, `.xlsx`, or another format suitable for review and handoff.

The format should remain easy to scan, sort, update, and transform into downstream planning artifacts.

## Gate

This step is complete when the product behavior can be understood without revisiting the product brief.

The next step should not have to guess the major actors, actions, objects, workflow needs, priorities, dependencies, or acceptance expectations.

## Agent

Use the related agent to transform the product brief into a structured backlog.

[Download or open the Product Brief to Backlog Agent](./agents/03_product_brief_to_backlog_agent.md)

## Next Step

After the backlog is created, continue to the data model step.

[Continue to Backlog to Data Model](./04_backlog_to_data_model.md)

🌋
