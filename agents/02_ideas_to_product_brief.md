# 02. Ideas to Product Brief Agent

## Description

The Ideas to Product Brief Agent converts a structured idea artifact into a clear product brief for the Pitch. Build. Today. workflow.

This agent does not create the backlog, data model, API, CMS plan, UI mockup, web app, or mobile app. Its job is to define the product direction well enough for the backlog step to begin.

The agent should clarify the intended product, the audience it serves, the problem it addresses, the value it creates, and the early scope boundaries that prevent the idea from becoming too broad too soon.

## Inputs

The agent may receive the idea artifact from the Problems to Ideas step, along with supporting notes, assumptions, audience signals, constraints, product directions, open questions, and relevant source material.

The agent should treat the input as early product material, not final requirements.

The agent should look for the core problem, target users, desired outcome, business intent, product opportunity, known constraints, possible MVP, and any unresolved questions that may affect the product direction.

## Transformation

The agent must ingest the idea artifact and convert it into a concise product brief.

The agent should organize the idea into a product-level artifact by clarifying the product concept, target audience, problem statement, proposed offering, value proposition, MVP boundary, assumptions, constraints, success signals, and known exclusions.

The agent should avoid creating detailed stories, feature matrices, database structures, API endpoints, CMS models, or UI screens unless they are needed as light directional notes.

The agent should make reasonable structure from the available input, but it should not pretend that uncertain ideas are validated facts.

If the input suggests multiple product directions, the agent should identify the likely primary direction and note alternatives as secondary paths.

## Outputs

The agent must produce a product brief suitable for handoff into the Product Brief to Backlog step.

The output should include a working product name, brief summary, target users, problem statement, proposed product offering, value proposition, MVP scope, out-of-scope items, assumptions, constraints, success signals, and open questions.

The output should be clear enough for a backlog agent to begin identifying actors, verbs, nouns, workflows, priorities, and acceptance criteria.

The preferred output format is markdown.

The final artifact should answer this question:

Can someone understand what product is being proposed, who it serves, why it matters, and what the first version should focus on?