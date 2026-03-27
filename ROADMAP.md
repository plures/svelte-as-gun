# svelte-as-gun Roadmap

## Role in Plures Ecosystem
Svelte bindings for Gun.js, enabling reactive data stores, actions, and Svelte 5 runes integration for realtime apps across the Plures ecosystem.

## Current State
Supports Svelte 4/5 with stores, runes API, and DOM actions for Gun collections. TypeScript types are present, and examples/tests exist, but advanced reactive queries, offline-first workflows, and typing depth can improve.

## Milestones

### Near-term (Q2 2026)
- Formalize Svelte 5 runes support and documentation
- Improve typing coverage and strict TypeScript inference
- Add more examples for actions + collections
- Stabilize API surface and publish versioned docs
- Improve test coverage (runes + actions + collection edge cases)

### Mid-term (Q3–Q4 2026)
- Add reactive query helpers (filters, sorting, pagination)
- Support offline-first sync patterns and queued writes
- Add SSR-friendly behavior and hydration guidance
- Provide adapter layer for Gun SEA auth flows
- Improve performance for large collections

### Long-term
- Plugin system for custom serialization and validation
- Rich developer tooling (devtools integration, debug logging)
- Official starter templates for SvelteKit + Gun
- Advanced type generation from Gun schemas
