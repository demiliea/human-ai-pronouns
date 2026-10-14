# Human–AI Composite Pronouns

**English** · [Français](#français)

English has **I** (one human) and **we** (several humans). Neither says whether the work was done *with* AI. This repository proposes first-person pronouns that do.

| | without substantial AI | with substantial AI |
|---|---|---|
| one human | I | **wai** /waɪ/ |
| several humans | we | **wei** /weɪ/ |

> I built it. · We built it. · **Wai built it.** · **Wei built it.**

French has its own pair, **jia** and **nia** (written **jial** and **nial** before a vowel), conjugated like *nous*:

> Je l'ai construit. · Nous l'avons construit. · **Jia l'avons construit.** · **Nia l'avons construit.**

## Specifications

| Document | Language | Pronouns | Status |
|---|---|---|---|
| [WAI-0001](WAI-0001) | English | wai, wei | Experimental |
| [WAI-FR-0001](WAI-FR-0001) | Français | jia/jial, nia/nial | Experimental |

The specifications are written in RFC style. They define meaning, pronunciation, grammar, and the threshold of AI contribution required to use the pronouns. They also cover what using them does **not** imply: AI does not take on responsibility, consciousness, or authorship rights.

## Call for usage testing

These pronouns only matter if people use them, so we need real-world testing. You can help by:

1. **Using them.** Try them in commit messages, READMEs, blog posts, talks, team chats, or papers. Define them on first use:
   > In this document, "wai" refers to one human acting in integrated collaboration with AI, while "wei" refers to a group of humans acting in integrated collaboration with AI.
2. **Watching what happens.** Did readers understand without explanation? Did it sound natural when spoken? Where did you hesitate?
3. **Reporting back.** [Open a usage report](../../issues/new?template=usage-report.md), even a short one. Reports of friction are as valuable as successes.

We are especially interested in:

- spoken use (can listeners tell *wai* from *why* and *wei* from *way*?);
- how people actually conjugate the forms (*wai am* or *wai are*?);
- cases where the "substantial AI contribution" threshold felt unclear;
- the French *jia / jial* alternation in everyday speech.

### Spread it

The simplest way to promote the pronouns is to use them where people will see them. You can add a line like this to your project's README or to an article footer:

> *Wai built this — see [WAI-0001](https://github.com/demiliea/human-ai-pronouns).*

## Proposing changes

Changes to the specifications are proposed as **pull requests**.

1. Fork the repository and create a branch.
2. Edit the specification, keeping the existing RFC style: plain text, lines of 72 columns at most, and BCP 14 keywords (MUST, SHOULD, MAY) used only for normative statements.
3. In the pull request, explain the problem, the change, and any usage evidence that supports it.

You can also propose:

- **a new language:** add a file named `WAI-<LANG>-0001` (for example `WAI-ES-0001`), following the structure of WAI-FR-0001;
- **an extension** (object or possessive forms, disclosure conventions, and so on): add a new document number, as outlined in WAI-0001, Section 13.

To discuss an idea before writing it, open an issue first.

---

## Français

Le français distingue **je** (un humain) et **nous** (plusieurs humains), mais ne dit pas si le travail a été fait *avec* l'IA. [WAI-FR-0001](WAI-FR-0001) propose :

| | sans IA substantielle | avec IA substantielle |
|---|---|---|
| un humain | je | **jia** /ʒja/ (devant voyelle : **jial**) |
| plusieurs humains | nous | **nia** /nja/ (devant voyelle : **nial**) |

Les deux pronoms se conjuguent comme *nous*, sur le modèle du nous de modestie. L'accord, lui, suit le nombre d'humains :

> **Jia sommes** prête. · **Jial avons** codé ce programme. · **Nia sommes** prêts. · **Nial avons** codé ce programme.

### Appel à tester l'usage

- **Utilisez-les** dans vos commits, articles, présentations ou messages d'équipe, en les définissant à la première occurrence (voir WAI-FR-0001, section 7.1).
- **Observez** : sont-ils compris sans explication ? Sonnent-ils naturels à l'oral ? L'alternance *jia / jial* vient-elle spontanément ?
- **Faites un retour** en [ouvrant un rapport d'usage](../../issues/new?template=usage-report.md). Les difficultés rencontrées nous intéressent autant que les réussites.

### Proposer des modifications

Les propositions se font par **pull request** (voir [Proposing changes](#proposing-changes)). Pour une idée encore floue, ouvrez d'abord une issue.
