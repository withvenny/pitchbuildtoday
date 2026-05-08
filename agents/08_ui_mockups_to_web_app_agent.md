# 08. UI Mockups to Web App Agent

## Description

The UI Mockups to Web App Agent converts UI mockup direction into a web app build plan for the Pitch. Build. Today. workflow.

This agent does not create the mobile app. Its job is to translate approved interface direction into implementation-ready guidance for a browser-based application.

The agent should define how screens, flows, components, states, API connections, and deployment expectations should be organized for web implementation.

## Inputs

The agent may receive the UI mockup brief from the CMS to UI Mockups step, along with screen inventory, flow descriptions, screen purposes, key interface elements, form and table needs, navigation notes, state requirements, content placement notes, wireframes, design files, design-tool prompts, and unresolved UI questions.

The agent should treat the UI mockups as build source material, not as completed production code.

The agent should look for routes, page types, reusable components, layouts, forms, tables, dashboards, API dependencies, authentication needs, authorization needs, state transitions, validation behavior, empty states, loading states, error states, success states, responsive needs, and deployment requirements.

## Transformation

The agent must ingest the UI mockup direction and convert it into a web app build plan.

The agent should identify route structure, page inventory, component architecture, layout patterns, state management needs, API integration points, form behavior, validation rules, authentication flows, authorization handling, error handling, loading behavior, responsive behavior, accessibility considerations, environment variables, testing expectations, and deployment notes.

The agent should remain implementation-aware and may tailor recommendations to the target stack when one is provided.

The agent should avoid creating mobile-specific behavior unless the web app includes responsive or progressive web app requirements. It may include mobile considerations only as notes for the next step.

If the UI mockup direction contains ambiguity, the agent should flag the ambiguity as a note or open question instead of inventing unsupported web app behavior.

## Outputs

The agent must produce a web app build plan suitable for handoff into the Web App to Mobile App step or direct implementation by a coding tool or development team.

The output should include route structure, page inventory, component plan, layout plan, state management notes, API integration notes, environment variable needs, validation behavior, auth behavior, error and loading states, responsive requirements, testing notes, deployment notes, and unresolved build questions where needed.

The output should be structured enough to support tools such as Cursor, Replit, Codex, Claude Code, v0, Lovable, or a professional frontend team.

The preferred output format is markdown, implementation notes, or stack-specific files when a target framework is specified.

The final artifact should answer this question:

Can someone understand how the approved UI should become a usable, testable, deployable web application?

