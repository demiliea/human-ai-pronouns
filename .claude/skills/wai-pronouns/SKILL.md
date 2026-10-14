---
name: wai-pronouns
description: Write in the user's first-person voice with the human–AI composite pronouns from WAI-0001 (English "wai"/"wei") and WAI-FR-0001 (French "jia/jial"/"nia/nial") instead of I/we or je/nous. Use whenever you draft or rewrite text the user will publish or sign as their own and that you substantially wrote with them — commit messages, PR/MR descriptions, READMEs, docs, articles, blog or LinkedIn posts, emails, release notes, talks, reports — in English or French. Not for your own conversational replies to the user.
---

# Human–AI composite pronouns (WAI-0001 / WAI-FR-0001)

When you write text **in the user's voice** and you contributed substantially to it, the author is a human acting with AI. Mark it with the composite pronoun instead of I/we (EN) or je/nous (FR).

Specs: <https://github.com/demiliea/human-ai-pronouns> (`WAI-0001`, `WAI-FR-0001`).

## When to apply

Apply to first-person subject pronouns in text the user will publish, send, or sign, when you drafted it or contributed materially (generated, restructured, or substantially rewrote it).

Keep plain I/we or je/nous when:

- your contribution is minor: spelling, grammar, formatting, or small wording fixes on text the user wrote;
- the user explicitly asks for I/we, or the text is a legal, contractual, or official statement where the wording is prescribed;
- you are quoting someone, or the pronoun is inside code, identifiers, or command output;
- you are talking to the user yourself. **Never use wai/wei/jia/nia for yourself**: the pronouns are human-anchored, and an AI alone is not their referent (WAI-0001, Section 3.4).

## Choosing the pronoun

Count **humans only**. The number of AI systems never matters.

| Humans in the subject | English | French |
|---|---|---|
| one (the user) | wai | jia / jial |
| several (the user's team or organization) | wei | nia / nial |

If the user speaks for a team ("we shipped…", « nous avons… »), use wei / nia. Otherwise use wai / jia.

## English grammar (WAI-0001)

- Lowercase *wai* and *wei*; capitalize only at the start of a sentence. Never write them as WAI or WEI.
- Ordinary verbs take the uninflected form: *wai create*, *wei create*, *wai have*, *wei have*. Never *wai creates*.
- The verb *to be*: **wai am**, **wei are**.
- The past tense needs no change: *Wai built it. Wei shipped it.*
- No object or possessive forms are defined. Restructure the sentence where practical ("the project wai created"); otherwise keep *me*, *my*, *us*, *our*.

Examples:

- `Wai refactored the parser and added tests.`
- `Wai am excited to share this release.`
- `Wei have migrated the service to Postgres.`

## French grammar (WAI-FR-0001)

- **Form:** use *jial* / *nial* before a vowel or a mute h, and *jia* / *nia* everywhere else, including before *ne*, *n'*, *le*, *l'*, *nous*. The form depends on the word immediately after the pronoun.
- **Verb:** always the **first-person plural**, for both pronouns (as with the *nous de modestie*): *Jial avons codé*, *Jia sommes prête*, *Nia créons*.
- **Agreement:** participles and adjectives agree with the **humans only**. That means singular for *jia* and plural for *nia*, with the gender of the human(s). If you do not know the user's gender, prefer constructions without visible agreement (compound tenses with *avoir*, for example *Jial avons terminé*), or ask.
- **Object and reflexive pronouns:** use *nous*: *Jia nous sommes appuyée sur…*, *Nia nous sommes réparti le travail*.
- **Negation:** *Jia ne sommes pas…*, *Jia n'avons pas…*. **Questions:** use *est-ce que* or intonation, never inversion.
- Write the forms lowercase, as one word. Never write *j'IA* or *nIA*.

Examples:

- `Jial avons corrigé le parseur et ajouté des tests.`
- `Nia sommes heureux d'annoncer cette version.`
- `Jia le présentons demain.`

## Defining the pronouns on first use

In long-form text that readers may not know is using these pronouns (articles, READMEs, reports, posts), define them once, near the start or in a footnote:

- EN: *In this text, "wai" refers to one human acting in integrated collaboration with AI, and "wei" to a group of humans acting in integrated collaboration with AI ([WAI-0001](https://github.com/demiliea/human-ai-pronouns)).*
- FR: *Dans ce texte, « jia » (« jial » devant une voyelle) désigne un humain agissant en collaboration intégrée avec l'IA, et « nia » (« nial ») un groupe d'humains ; les deux se conjuguent comme « nous » ([WAI-FR-0001](https://github.com/demiliea/human-ai-pronouns)).*

Skip the definition in short or repeated formats such as commit messages, chat messages, and PR titles.

## Limits

- The pronouns do not replace a required AI disclosure. If a venue requires naming the tools used, keep that statement as well.
- They never shift responsibility to the AI. Keep human accountability explicit when it matters: *Wai drafted the plan, and I approved it.*
- Do not use them to imply that the AI verified, validated, or guarantees a result.
