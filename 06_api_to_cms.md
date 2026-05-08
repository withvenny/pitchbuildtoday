# 06. API to CMS

## Purpose

This step converts an API design package into a CMS plan.

The goal is to define how operators, admins, editors, or internal users will manage the product without needing to change code.

## Accepted Inputs

The agent may ingest the API design package from the previous step, along with API resources, endpoints, methods, authentication rules, authorization rules, validation rules, error states, integrations, and unresolved API questions.

The input should provide enough system clarity for the agent to identify what needs to be managed through an operator-facing control layer.

## Transformation

The agent is responsible for converting the API design package into a CMS plan.

The agent should identify manageable resources, admin roles, content types, settings, workflows, permissions, approval needs, dashboards, templates, and operational controls.

## Output

The output is a CMS plan that gives the next step enough context to create UI mockups.

The CMS plan should help a reader understand what operators need to manage, how they should manage it, and what controls are needed to support the product after launch.

## Output Format

The preferred output may be saved as `.md`, `.json`, `.yaml`, `.tsx`, or another format suitable for review, implementation, and handoff.

The format should remain clear enough to support future UI mockups, frontend planning, and admin experience design.

## Gate

This step is complete when the product’s admin needs, manageable resources, roles, permissions, content structures, settings, and operational workflows can be understood without revisiting the API design package.

The next step should not have to guess what the CMS or operator interface needs to support.

## Agent

Use the related agent to transform the API design package into a CMS plan.

[Download or open the API to CMS Agent](./agents/06_api_to_cms_agent.md)

## Next Step

After the CMS plan is created, continue to the UI mockups step.

[Continue to CMS to UI Mockups](./07_cms_to_ui_mockups.md)

🌋
