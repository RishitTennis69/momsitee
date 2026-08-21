# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML, CSS, and browser JavaScript. Posts are stored in `localStorage`; there is no server-side database or authentication layer in the current project.

## Users

- Parents and caregivers looking for clear, reassuring pediatric dental guidance.
- A small-site editor who writes, drafts, publishes, updates, and removes journal posts through the local admin interface.

## Product Purpose

The Smile Journal makes practical pediatric dental guidance easy for families to browse, search, and read, while giving its editor a lightweight publishing workspace.

## Positioning

The product presents dental guidance as a calm, human editorial journal rather than a clinic-marketing funnel or a generic health-content portal.

## Operating Context

Readers arrive to scan recent articles, browse by topic, search for a concern, and open a full post. The editor uses the admin dashboard to manage publication status and article content in the same browser where the data is stored.

## Capabilities and Constraints

- Readers can search posts, filter by category, browse article previews, and read complete posts.
- The admin can create, edit, publish, draft, and delete posts and attach image or video media.
- Existing article copy, categories, dates, and publishing behavior must remain functional.
- Data and authentication are local-browser demonstrations, not production-grade account or storage systems.
- No clinic identity, patient service offer, deployment target, or commercial claim has been supplied; future work must not fabricate them.

## Brand Commitments

- Preserve the name “The Smile Journal.”
- Preserve a teal/green identity within a bright white or warm-white interface.
- The experience should feel editorial, clear, calm, premium, and family-friendly without looking childish or like a generic AI-generated startup.
- Use one unified, characterful type family rather than a decorative display/body mismatch.
- Avoid textured backgrounds, excessive pills, stock-dashboard patterns, gratuitous color, emojis as interface icons, heavy blur, and decorative technology effects.

## Evidence on Hand

- Four built-in sample articles and their complete body copy in `index.html`.
- Existing reader and admin workflows in `index.html` and `admin.html`.
- Existing cover-image URLs are implementation evidence only; the user specifically identified the current imagery as visually unhelpful, so imagery may be removed or deemphasized without replacing it with invented proof.
- No testimonials, customer data, clinic photography, benchmarks, or externally verified medical claims were supplied.

## Product Principles

1. Put trustworthy reading and clear editorial hierarchy ahead of decoration.
2. Keep discovery controls together so search, topic filtering, and post management feel like one coherent workflow.
3. Use content and typography—not stock imagery or card chrome—to establish the journal’s identity.
4. Preserve calm familiarity for parents while giving the editor dense, practical controls.
5. Make every interactive state legible, keyboard accessible, and responsive.

## Accessibility & Inclusion

Use semantic controls, visible focus states, readable contrast, responsive layouts, and reduced-motion support. Language should remain plain and reassuring for caregivers without assuming specialist dental knowledge.
