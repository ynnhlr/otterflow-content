# Otterflow Content Repository

## Project purpose

This repository contains the English and Danish blog content for Otterflow.

Otterflow helps freelancers and other independent professionals move through one clear workflow:

**work log -> client review -> client approval -> invoice**

The product is focused on making the handoff between completed work and invoicing clearer. It is not positioned as a full project-management, CRM, or accounting platform.

Treat [otterflow.app](https://www.otterflow.app/) as the authoritative source for current product features, positioning, pricing, and terminology. Check the website when product details matter. If the website is unclear, inconsistent, or does not answer a material question, ask the user instead of guessing.

## Scope of work

- Work in this repository is limited to blog content in English and Danish.
- Typical tasks include planning, drafting, editing, translating, and validating blog articles.
- Do not expand the repository into unrelated documentation, product code, or marketing assets unless the user explicitly requests it.
- Only edit files. Do not create branches, commits, pull requests, or make other Git changes unless the user changes this instruction.

## Collaboration and approval

- Ask before making substantive editorial, structural, positioning, or product-related decisions that the user's request does not already settle.
- If the user gives a detailed brief, follow it without asking questions that the brief already answers.
- For open-ended article requests, research and propose a topic, angle, or outline, then ask for approval before drafting.
- When the user already provides the topic or direction, add useful research and structural suggestions while preserving their intent.
- Surface doubts about facts, claims, audience, or product behavior instead of filling gaps with assumptions.

## Bilingual publishing workflow

- Every article must have both an English and a Danish version.
- Write and finalize the English article first.
- Create the Danish version only after the English direction and content are settled.
- Translate naturally for a Danish reader. Preserve meaning, structure, and tone, but do not force a word-for-word translation.
- Keep paired articles aligned when one version changes.
- Store English articles in `blog/en/` and Danish articles in `blog/da/`.
- The Danish front matter must include a `translationKey` whose value matches the English article's `slug`.

## Editorial voice

Use the existing articles as the primary style reference. The established Otterflow voice is:

- Calm, clear, conversational, and practical.
- Written directly to freelancers and independent professionals in plain language.
- Helpful and confident without sounding corporate, aggressive, or over-polished.
- Empathetic about awkward client conversations and administrative friction.
- Focused on one concrete problem and a cleaner workflow for solving it.
- Lightly personable where natural, including occasional understated humor, but never gimmicky.

Follow these writing patterns:

- Open with a recognizable situation, tension, or simple product idea.
- Use short paragraphs and mostly short sentences.
- Use descriptive `##` headings to move the argument forward.
- Use lists when they make work details, problems, or process steps easier to scan.
- Use bold standalone statements sparingly for the central idea or workflow.
- Explain the problem before introducing Otterflow.
- Keep product mentions focused and relevant instead of turning the article into a sales pitch.
- Prefer concrete words such as work, review, approval, client, and invoice over abstract business jargon.
- End by reinforcing the practical benefit: greater clarity, less friction, or a cleaner path to payment.

Avoid:

- Hype, exaggerated promises, fear-based language, and unsupported claims.
- Dense paragraphs, unnecessary jargon, or generic SEO filler.
- Presenting clients as difficult or unreasonable; their need for clarity is legitimate.
- Positioning Otterflow as an all-in-one system.
- Inventing features, integrations, pricing, testimonials, statistics, or customer outcomes.

## Article structure and metadata

Follow the front-matter structure already used by articles in the relevant locale. Check that each new or edited article has:

- A unique, readable, lowercase slug using hyphens.
- A clear title aligned with the article's search intent.
- A concise description that accurately summarizes the article and works as a search snippet.
- A valid `publishedAt` date in `YYYY-MM-DD` format.
- The established localized author name: `Otterflow Team` in English and `Otterflow-teamet` in Danish.
- Relevant, localized categories consistent with existing articles.
- A `coverImage` field.
- A matching Danish `translationKey` pointing to the English slug.

Preserve existing metadata unless the task requires a change. Keep English and Danish publication dates and topic categorization aligned where appropriate.

## Images

- Leave final image creation and editing to the user.
- For a new draft, use an explicit cover-image placeholder rather than inventing a URL or generating an image.
- If placeholder syntax could affect publishing or validation, ask the user which value to use.
- Do not create, download, or modify image files unless the user changes this instruction.

## Required quality checks

Before handing off an article, check:

1. English and Danish spelling, grammar, punctuation, and readability.
2. All links for correct destinations and appropriate link text.
3. Front matter for syntax, required fields, slug pairing, dates, authors, categories, and translation keys.
4. SEO basics: clear search intent, accurate title and description, useful headings, natural key terminology, and no keyword stuffing.
5. Translation quality: natural Danish, preserved meaning, consistent terminology, matching structure, and no untranslated English left accidentally.
6. Product claims against [otterflow.app](https://www.otterflow.app/), asking the user when anything remains uncertain.

Report any unresolved placeholder, factual uncertainty, or decision that still needs the user's approval.
