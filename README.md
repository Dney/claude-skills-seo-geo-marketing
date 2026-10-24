# Geeks360 Claude skills

The Claude skills we use at Geeks360 for client work: SEO, GEO, ads, websites, email and agent workflows.
A skill is a packaged set of instructions Claude loads when a task matches it.

**SEO** is search engine optimization for Google and Bing. **GEO** (generative engine optimization) is getting a
brand found and cited in AI answers: ChatGPT, Perplexity, Google AI Overviews, Copilot.

Updated 24 Oct 2026. 57 skills. Per-client skills are shown as one line with the number of client sites.
This page lists skills only; it holds no keys, accounts or client data.

## SEO + GEO content

| Name | Skill id | What it does |
|---|---|---|
| SEO + GEO Blog Article Writer | `<client>-blog-writer` (11 sites) | Keyword and SERP research first, then an answer-first article built to rank in Google and be quoted by AI search: FAQ with schema, sources, internal links, ready for WordPress, Shopify or Wix. One skill per client, with that client's voice and compliance rules. |
| SEO + GEO Meta Tag Writer | `seo-meta-writer` | Title tags, meta descriptions, H1s, Open Graph and schema headlines for Google, Bing and AI search, written for clicks, not templates. |
| SEO + GEO Page Rewrite | `ur-content-rewrite` (1 site) | Rewrites service, location, FAQ, blog and team pages of a law firm site against target queries. |
| GEO Reddit Presence Writer | `reddit-comment-writer`, `<client>-reddit-*` (3) | Natural, human Reddit comments and posts for brand and expert accounts. Reddit threads are often cited by AI search. |

## SEO off-page

| Name | Skill id | What it does |
|---|---|---|
| SEO Backlink Article Writer | `<client>-backlink-writer` (8 sites) | Value-first editorial guest posts for third-party sites that link back to the client. |
| SEO Link Guard (negative SEO and disavow) | `geeks360-linkguard` | Monthly negative-SEO check for geeks360.net: fresh backlink data, spam measurement, disavow file rebuild and upload after approval. |

## E-commerce SEO

| Name | Skill id | What it does |
|---|---|---|
| E-commerce SEO Category Research | `<client>-category-research` | Sitemap parsing, seed keywords and a content plan per catalog category. |
| E-commerce SEO Product Content | `<client>-product-content`, `<client>-general-content` | Product descriptions, specifications and SEO meta tags for a large B2B catalog. |
| E-commerce SEO Product FAQ | `<client>-faq` | FAQ blocks for product pages with FAQPage schema. |

## SEO reporting and data

| Name | Skill id | What it does |
|---|---|---|
| SEO Monthly Report | `<client>-monthly-report` (8 sites) | The monthly SEO status deck (PPTX) in each client's style, plus a keyword positions tracker (XLSX). |
| SEO Analytics Data Access | `seo-accesses` | Pulls data from Google Search Console, GA4, Microsoft Clarity, Ahrefs and SE Ranking. |
| SEO + GEO Marketing Page Rulebook | `marketing-pages` | Rules for marketing site pages by class (campaign landers, product pages, programmatic SEO, editorial): indexing, sitemap and robots, AI-readable surfaces, attribution, conversion. Third-party, from dzhng/skills. |

## Ads and creative

| Name | Skill id | What it does |
|---|---|---|
| Meta Ad Creatives (end to end) | `meta-ad-creatives` | Brief, research, idea plan, photos, statics, Stories, carousels, video, review rounds, packaging and handoff for Meta (Facebook and Instagram). Includes design rules, copy rules and a profile per brand. |
| Meta Static Ad Design | `static-ad-design` | Rules and a reference library for static ads (Feed, Stories, Reels) that look like top-performing ads, not agency templates. |
| Meta Ad Banner Creator | `meta-ad-banner-creator` | Production-ready banners for Facebook and Instagram campaigns. |
| Meta Ad Copy | `social-media-ad-content` | Short, scroll-stopping headlines, subtitles and bullet points by audience segment. |
| Blog Hero Image Prompts | `blog-hero-image-prompt-generator` | Three concept directions with full prompts for AI-generated blog hero images. |
| Launch Video | `launch-video` | A motion-graphics launch or promo video with music for a product. Third-party, from dzhng/skills. |

## Websites

| Name | Skill id | What it does |
|---|---|---|
| WordPress ACF Site Builder | `build-wp-acf-site` | WordPress sites on a clean custom ACF Pro theme: flexible-content page sections, acf-json as the source of truth. |
| Client Site Design (HTML first) | `client-site-design` | Designs client pages in HTML before WordPress, so every page stays in one style. Also used when agents produce pages or graphics. |
| Server Access (SSH and WP-CLI) | `geeks-ssh` | Shell and WP-CLI access to our hosting server for diagnostics and maintenance. |

## Email

| Name | Skill id | What it does |
|---|---|---|
| Client Email Writer | `client-email` | Emails and replies in Darya's voice: friendly, short, no filler. |

## Visual QA

| Name | Skill id | What it does |
|---|---|---|
| Screenshot Compare | `compare-screenshots` | Judges which of two versions is less wrong, with crops, zoom and measurements. Third-party, from dzhng/skills. |
| Fresh-Eyes Screenshot Critique | `screenshot-critique` | An unprimed second opinion on visual work before it is called done. Third-party, from dzhng/skills. |
| Preview Shots | `preview-shots` | Opens a set of screenshots or renders in one macOS Preview window. Third-party, from dzhng/skills. |

## Agent workflow

| Name | Skill id | What it does |
|---|---|---|
| Grill Me (plan stress test) | `grill-me` | Interviews you about a plan or design until every open branch is decided. |
| Session Atlas | `session-atlas` | Rebuilds the private index of past Claude Code and Codex sessions across our machines. |
| Jevify (cheaper AI decisions) | `jevify` | Finds LLM calls that a cheaper typed decision model could replace, and designs a fair evaluation. |
| HiveMind Notify | `hivemind-notify` | Sends a HiveMind notification when asked. |
| HiveMind Tag | `hivemind-tag` | Tags a session or records a URL of a service it started. |

## Also installed

Anthropic built-in skills (Word, Excel, PowerPoint, PDF, Google Workspace, deep research, skill creator, MCP builder and
others) and the plugins pstack, Figma, Canva, last30days and Build with WordPress.
