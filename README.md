# Cloud AI Image Generation Notes

Notes distilled from a `/DE3/` (DALL-E 3 / Cloud AI Image Generation General,
4chan `/g/`-style) thread — hosted/cloud image generators, as opposed to the
locally-run models covered in the sibling
[stable-diffusion-notes](https://github.com/abdussamikhan1999-stack/stable-diffusion-notes)
repo.

See [LINKS.md](LINKS.md) for the full raw link list, organized by section.

## The tools, by access model

**Free, no account gymnastics:**
- **ChatGPT** (chatgpt.com) — OpenAI's GPT-Image 2 via chat interface.
- **Microsoft Designer Image Creator** / **Copilot** / **Bing Image Create**
  — three different Microsoft surfaces for the same underlying image models
  (MAI-Image and/or OpenAI models depending on surface) — if one is
  rate-limited/down, the others are worth trying since they may share quota
  pools or not, inconsistently.
- **Gemini** (gemini.google.com) / **AI Studio** (aistudio.google.com) /
  **Flow** (labs.google/fx/tools/flow) — Google's "Nano Banana Pro/2" image
  models across three different surfaces: Gemini is the consumer chat app,
  AI Studio is the developer-facing playground (more control, less
  hand-holding), Flow is Google's dedicated creative/video-leaning tool.
- **Meta AI** (ai.meta.com) — Meta's "Musespark" image model.
- **Perchance** (perchance.org) — free, no-login, community-built generators
  — different tradeoff from the corporate tools: less polished/consistent,
  but no account and often no content filter parity with the big providers.

**Paid:**
- **Midjourney** — still the aesthetic/quality benchmark many people default
  to for stylized or artistic output; Discord- or web-based, subscription
  required.
- **NovelAI** — paid, notable for leaning into anime/illustration style and
  historically looser content policies than the mainstream corporate tools.

**Adjacent (AI video, not image):**
- **PixVerse** and **Hailuo AI Video** — cloud text/image-to-video, listed
  alongside the image tools since the same "type a prompt, get media" model
  applies.

## Picking one

- Want the current best general-purpose quality with zero cost/signup
  friction → start with ChatGPT or Gemini, compare outputs, use whichever
  Nano Banana / GPT-Image surface isn't rate-limiting you that day.
- Want the most "artistic"/stylized default aesthetic → Midjourney, if
  you're willing to pay.
- Want anime-leaning or the loosest content policy among the mainstream
  paid options → NovelAI.
- Want zero-friction/anonymous and don't mind rougher, more variable output
  → Perchance.
- Want a paper trail of what specific generator/style to try on Perchance
  → see the Perchance generator list below rather than guessing from the
  homepage.

## Prompting help

- **DALL-E prompt generator** (tipseason.com) — a free tool that turns a
  simple idea + optional style choice into a fuller, more descriptive
  prompt; part of a family of similar generators for Midjourney/Gemini/Adobe
  Firefly. Useful as a starting template to edit, not a black box to trust
  blindly.
- **DALL-E 3 image generation guide** — four image files (catbox.moe links,
  not fetchable as text from here) — presumably a visual prompting
  cheat-sheet; open directly to view.
- **Perchance generator list** (pastebin) — ~21 image generators cataloged
  by type (anime-specific, general text-to-image, style-specific like
  flux/low-poly), plus chatbot generators and documentation for people who
  want to *build* their own Perchance generator (snippets, metadata,
  plugins, text-to-image integration). The actually useful part if
  Perchance's default generator doesn't fit what you want — browse this list
  for a more specific one instead.

## Related boards (if this general doesn't cover your use case)

The thread cross-links: video-game-AI-art (`/vg/vig`), a dedicated
DALL-E-focused board (`/co/dall-e`), a bad-image-fails/general AI board-
fun board (`/trash/aibf`), adult-content AI art (`/aco/mmai`), and a
toys/figures-adjacent general (`/tg/slop`) — same tool landscape, different
community focus/content norms.
