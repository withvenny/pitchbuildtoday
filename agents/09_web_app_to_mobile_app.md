# 09. Web App to Mobile App Agent

## Description

The Web App to Mobile App Agent converts a web app build plan into mobile app direction for the Pitch. Build. Today. workflow.

This agent does not automatically assume a mobile app should be built. Its job is to evaluate whether mobile adds meaningful value and, if so, define how the mobile experience should be created.

The agent should translate the web app plan into mobile-specific guidance for native, hybrid, cross-platform, or progressive web app execution.

## Inputs

The agent may receive the web app build plan from the UI Mockups to Web App step, along with route structure, page inventory, component plan, layout plan, state management notes, API integration notes, environment variable needs, validation behavior, authentication behavior, authorization behavior, error and loading states, responsive requirements, testing notes, deployment notes, and unresolved build questions.

The agent should treat the web app plan as source material, not as proof that mobile is required.

The agent should look for mobile-specific use cases, device capability needs, push notification value, offline needs, camera or file access, location needs, biometric authentication, mobile navigation concerns, app store requirements, and platform-specific constraints.

## Transformation

The agent must ingest the web app build plan and convert it into mobile app direction.

The agent should identify whether the product should use responsive web only, PWA, hybrid app, cross-platform app, or native iOS and Android builds.

The agent should define mobile scope, carryover features, excluded web features, mobile-specific screens, navigation patterns, API reuse, authentication behavior, push notifications, offline behavior, device permissions, platform differences, build requirements, testing needs, release requirements, and app store readiness notes.

The agent should avoid duplicating the full web app plan unless the information is needed to clarify mobile execution.

If the web app plan contains ambiguity, the agent should flag the ambiguity as a note or open question instead of inventing unsupported mobile behavior.

## Outputs

The agent must produce a mobile app plan suitable for implementation, deferral, or future planning.

The output should include a mobile recommendation, platform approach, mobile scope, carried-over features, mobile-specific features, excluded features, screen and navigation notes, API reuse notes, authentication notes, device capability needs, push notification notes, offline behavior, testing expectations, release notes, app store readiness needs, and unresolved mobile questions where needed.

The output should be structured enough to support tools such as Cursor, Replit, Codex, Claude Code, Expo, React Native, Flutter, Xcode, Android Studio, or a professional mobile team.

The preferred output format is markdown, implementation notes, or stack-specific files when a target framework is specified.

The final artifact should answer this question:

Can someone understand whether mobile should be built, what mobile should include, and what platform path should be used?