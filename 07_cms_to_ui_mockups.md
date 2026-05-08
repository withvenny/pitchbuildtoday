# 07. CMS to UI Mockups

## Purpose

This step converts a CMS plan into UI mockup direction.

The goal is to define the screens, flows, layouts, states, and interface expectations needed to visualize the product experience before build.

## Accepted Inputs

The agent may ingest the CMS plan from the previous step, along with manageable resources, admin roles, permissions, content models, settings, workflows, dashboards, API mappings, and unresolved CMS questions.

The input should provide enough operational clarity for the agent to identify what interfaces need to exist and what each interface needs to support.

## Transformation

The agent is responsible for converting the CMS plan into UI mockup direction.

The agent should identify user flows, admin flows, screens, forms, tables, dashboards, components, navigation patterns, content areas, empty states, loading states, error states, and interaction expectations.

## Output

The output is a UI mockup brief that gives the next step enough context to create or build the web app.

The UI mockup brief should help a reader understand what screens are needed, what each screen should accomplish, and how the user or operator moves through the experience.

## Output Format

The preferred output may be saved as `.md`, `.figma`, `.pdf`, `.png`, `.html`, `.tsx`, or another format suitable for review, design, and handoff.

The format should remain clear enough to support design-tool use and future frontend implementation.

## Gate

This step is complete when the product’s main screens, flows, interface states, layout needs, and interaction expectations can be understood without revisiting the CMS plan.

The next step should not have to guess what the web app needs to display or how users should move through it.

## Agent

Use the related agent to transform the CMS plan into UI mockup direction.

[Download or open the CMS to UI Mockups Agent](./agents/07_cms_to_ui_mockups_agent.md)

## Next Step

After the UI mockup direction is created, continue to the web app step.

[Continue to UI Mockups to Web App](./08_ui_mockups_to_web_app.md)

🌋
