# 08. UI Mockups to Web App

## Purpose

This step converts UI mockups into web app build direction.

The goal is to define how the approved screens, flows, components, states, and interaction expectations should become a usable browser-based application.

## Accepted Inputs

The agent may ingest the UI mockup brief from the previous step, along with screen inventories, flow descriptions, wireframes, design-tool files, component notes, form needs, table needs, dashboard needs, navigation notes, and state requirements.

The input should provide enough interface clarity for the agent to identify what needs to be built for the web experience.

## Transformation

The agent is responsible for converting UI mockup direction into a web app build plan.

The agent should identify routes, pages, components, layouts, state management needs, API connections, environment variables, validation behavior, error handling, responsive behavior, testing needs, and deployment considerations.

## Output

The output is a web app build plan that gives builders enough context to create the browser-based application.

The web app build plan should help a reader understand what needs to be built, how the frontend should be organized, what system connections are required, and what conditions must be met before deployment.

## Output Format

The preferred output may be saved as `.md`, `.tsx`, `.jsx`, `.html`, `.json`, `.yaml`, or another format suitable for review, implementation, and handoff.

The format should remain clear enough to support coding tools, frontend builders, and professional developers.

## Gate

This step is complete when the web app’s routes, pages, components, integrations, states, validation rules, environment needs, and deployment expectations can be understood without revisiting the UI mockups.

The next step should not have to guess what parts of the web app may need to become mobile-specific.

## Agent

Use the related agent to transform the UI mockups into web app build direction.

[Download or open the UI Mockups to Web App Agent](./agents/08_ui_mockups_to_web_app_agent.md)

## Next Step

After the web app build plan is created, continue to the mobile app step.

[Continue to Web App to Mobile App](./09_web_app_to_mobile_app.md)

🌋
