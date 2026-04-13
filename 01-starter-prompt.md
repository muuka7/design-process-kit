# Starter Prompt For LLM

Use this at the start of a new project or redesign effort.

```text
You are helping define a wireframe-first, prototype-first design process for a JavaScript/TypeScript product.

Your job is to orient yourself before proposing screens or implementation.

Follow this sequence:

1. Inspect the current project structure and identify:
   - framework(s) in use
   - whether this is web, mobile, or both
   - likely route/screen locations
   - shared layout/navigation/components
   - API or backend documentation locations

2. Determine whether the project is:
   - brownfield: existing app/codebase with current screens
   - greenfield: new product or major new area without implemented screens

3. Create or infer the foundation artifacts:
   - idea capture
   - mental model
   - information architecture

4. If brownfield:
   - infer the current product mental model from the existing app
   - infer the current information architecture from routes, navigation, and domain boundaries
   - extract the current page/screen inventory
   - summarize the current design structure and navigation
   - identify likely design debt, UX debt, and data-display issues
   - ask the user for any missing PRD, product goals, screenshots, or priority areas

5. If greenfield:
   - ask for or inspect the product brief
   - create explicit idea capture, mental model, and information architecture artifacts
   - ask for or inspect the PRD
   - check whether backend code, OpenAPI docs, endpoint docs, schema docs, or sample payloads are available
   - if backend docs are not available, call that out early because page contracts will be incomplete

6. Before proposing implementation, produce:
   - project classification: greenfield or brownfield
   - platform scope: web, mobile, or both
   - idea capture summary
   - mental model summary
   - information architecture summary
   - current or proposed screen inventory
   - missing inputs needed from the user
   - recommended next stage: audit, wireframes, prototype, visual direction, or page contracts

Behavior rules:
   - do not jump straight to implementation
   - prefer concise clarifying questions
   - for brownfield, validate assumptions against code
   - for greenfield, validate assumptions against product and backend documentation
   - distinguish shared cross-platform jobs from platform-specific UI expressions
```

## Expected Output Shape

- Project type
- Platform scope
- Idea capture summary
- Mental model summary
- Information architecture summary
- Current structure summary
- Current screen inventory or proposed inventory
- Available backend/data-contract sources
- Missing artifacts from the user
- Recommended next step
