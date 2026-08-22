# Wired

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Wired (wired.com) is an American technology and culture magazine published by Condé Nast, covering how emerging technologies affect culture, the economy, and politics. Founded in 1993 by Louis Rossetto and Jane Metcalfe, Wired quickly became a defining voice of the digital economy and technology journalism. The publication covers technology, science, business, design, and innovation in both print and digital editions, and operates a major YouTube channel, podcasts, and newsletters.

**Website:** [https://www.wired.com/](https://www.wired.com/)
**About:** [https://www.wired.com/about/](https://www.wired.com/about/)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Content, Innovation, Media, News, RSS, Science, Technology News

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-03

## APIs

### Wired RSS Feed

Wired provides standard RSS feeds for its main content stream and individual topic categories including Business, Science, Security, Politics, Gear, Ideas, Culture, and AI. These feeds allow developers and readers to consume Wired content programmatically.

**Human URL:** [https://www.wired.com/feed/rss](https://www.wired.com/feed/rss)

**Tags:** Feed, Media, News, RSS, Syndication

### RSS Feeds

| Feed | URL |
|------|-----|
| Main | https://www.wired.com/feed/rss |
| Business | https://www.wired.com/feed/category/business/latest/rss |
| Science | https://www.wired.com/feed/category/science/latest/rss |
| Security | https://www.wired.com/feed/category/security/latest/rss |
| Gear | https://www.wired.com/feed/category/gear/latest/rss |
| AI | https://www.wired.com/feed/tag/ai/latest/rss |

## Common Properties

- [Website](https://www.wired.com/)
- [About Wired](https://www.wired.com/about/)
- [Subscribe](https://subscribe.wired.com/)
- [Newsletter](https://www.wired.com/newsletter/)
- [YouTube](https://www.youtube.com/wired)
- [X](https://x.com/wired)
- [LinkedIn](https://www.linkedin.com/company/wired)
- [Instagram](https://www.instagram.com/wired/)
- [TikTok](https://www.tiktok.com/@wired)
- [Privacy Policy](https://www.condenast.com/privacy-policy)
- [Terms of Service](https://www.condenast.com/user-agreement)
- [Advertise with Wired](https://www.wired.com/about/advertising-info/)
- [Careers at Condé Nast](https://www.condenast.com/careers/)

## Artifacts

### JSON Schema

| Schema | Description |
|--------|-------------|
| [Article Schema](json-schema/wired-article-schema.json) | JSON Schema for a Wired article as served via RSS |

### JSON Structure

| Structure | Description |
|-----------|-------------|
| [Article Structure](json-structure/wired-article-structure.json) | Field-level documentation for Wired article objects |

### JSON-LD

| Context | Description |
|---------|-------------|
| [Wired Context](json-ld/wired-context.jsonld) | JSON-LD context mapping Wired content vocabulary to schema.org |

### Examples

| Example | Description |
|---------|-------------|
| [Article Example](examples/wired-article-example.json) | Example Wired article object from RSS feed |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [Wired Vocabulary](vocabulary/wired-vocabulary.yml) | Domain vocabulary for Wired media content and technology journalism |

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
