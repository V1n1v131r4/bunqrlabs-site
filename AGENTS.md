# AGENTS.md — BunQr Intelligence Website

## Purpose
This repository contains the public website for **BunQr Intelligence** (formerly BunQr Labs). Treat it as a production-facing corporate website. Prioritize correctness, restrained changes, brand consistency, accessibility, and maintainability.

## Business and positioning
- Brand: **BunQr Intelligence**. Do not reintroduce **BunQr Labs** in customer-facing copy unless explicitly required for historical context.
- Positioning: a specialized boutique operating across **Cybersecurity, Digital Intelligence, OPSEC, and AI Enablement**.
- Business areas include specialized services, professional training/Academy, and research. Do not imply the company only sells courses.
- Tone: confident, technically credible, clear, professional, and understated. Avoid exaggerated claims, invented certifications, clients, testimonials, partnerships, or metrics.
- Default public-facing site language: follow the language already used by each page (primarily Brazilian Portuguese). Do not translate unrelated sections.

## First steps on every task
1. Inspect the repository structure, relevant HTML/CSS/JS/assets, and existing conventions before proposing changes.
2. Identify the source of truth for shared components and styles. Do not assume a framework or build pipeline.
3. Summarize the proposed files and modifications before implementing anything substantial.
4. Preserve existing behavior and visual alignment. Do not opportunistically refactor unrelated code.
5. When instructions conflict with existing implementation or assets, ask before guessing.

## Visual and UX guidelines
- Preserve the established **dark blue and black** visual identity, typography, spacing, navigation, and responsive behavior as implemented in the repository.
- Reuse existing CSS variables, classes, components, and assets when appropriate. Do not invent new brand colors, gradients, logos, or imagery.
- Use the **actual BunQr logo** from approved repository assets. Never redraw, approximate, or generate a substitute logo.
- Maintain consistent desktop, tablet, and mobile layouts; check for overflow, broken alignment, and unintended stacking.
- Keep semantic HTML, readable contrast, keyboard navigation, meaningful alt text, and sensible loading/performance practices.
- Avoid adding libraries or dependencies for simple visual changes without approval.

## Content and evidence standards
- Do not fabricate client relationships, endorsements, contracts, outcomes, case studies, institutional affiliations, or claims of authorization.
- Distinguish between an **organization that contracted BunQr** and an **organization employing an individual who attended BunQr training**.
- Do not describe all institutions as direct clients or partners if the relationship is not verified.
- Logos and names of third-party organizations may require permission and must follow applicable brand-use guidelines. Flag uncertain authorization rather than assuming it.
- Any legal or brand-use disclaimer should be reviewed by the project owner before publication.

## Homepage: institutional credibility section (planned)
The project owner wants a unified visual section presenting organizations connected to BunQr's trajectory across services and education, **without separating the logos by business line**.

Suggested copy (subject to owner approval):

**Heading:** Instituições que fazem parte da nossa trajetória

**Supporting text:** Da formação de profissionais à entrega de soluções especializadas, nossa experiência conecta a BunQr Intelligence a organizações de diferentes setores.

**Possible footnote:** As marcas representam diferentes formas de relacionamento profissional e educacional. Sua exibição não implica necessariamente parceria institucional ou endosso.

Implementation expectations:
- Inspect the current homepage and propose a location that works with the existing information hierarchy.
- Use a restrained, responsive logo grid that fits the current design system.
- Do not split logos into Academy versus Services.
- Use only owner-provided/approved institutional logos; do not invent placeholders that could be mistaken for real institutions.
- Avoid asserting client status for all logos. Confirm wording and authorization with the owner before publication.
- **This section is a planned task, not permission to implement it automatically.**

## Editing and review workflow
- For substantive changes, **propose the approach and wait for explicit approval before editing**.
- Scope changes to the requested page or component; preserve all unrelated content and functionality.
- Show which files changed and summarize the changes after implementation.
- Run available checks/builds where applicable, and inspect responsive behavior when tooling allows. Clearly state what could not be verified.
- Do not commit, merge, deploy, modify production configuration, or introduce external services without explicit authorization.
- Never expose secrets, tokens, internal credentials, customer-sensitive details, or private investigation data in site assets or commits.

## Important historical lesson
Previous site revisions unintentionally changed the alignment and grouping of elements on `about.html`, including the logo, served sectors, and focus areas beside the “Quem Somos” content. **Preserve the intended side-by-side desktop composition and responsive behavior** when touching that page. Similarly, do not alter alignment on `ai-enablement` pages without checking the existing design.

## If anything is unclear
Ask a targeted question or present a small proposal rather than making a high-impact assumption. The project owner prefers approving consequential changes, particularly anything involving brand representation, institutional logos, and production publication.
