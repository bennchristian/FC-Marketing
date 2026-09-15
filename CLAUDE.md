# FC-Marketing — content workspace

This repo is where all social content work happens. The skills it references are
installed globally in `~/.claude/skills/` and are available in any session;
refresh them with `~/.claude/skills/update-social-skills.sh`.

## Read these first, every session

- `brand/brand-profile.md` — who this brand is, who it serves, what it will and won't say
- `brand/voice.md` — the actual voice, extracted from real published writing
- `brand/audience.md` — who we're talking to
- `brand/content-pillars.md` — the 3–5 recurring themes

If a file above is missing, say so and offer to run the skill that creates it
(`brand-profile`, `voice-builder`, `audience-research`, `content-pillars`)
rather than inventing the content.

## Platforms

LinkedIn and Instagram/Reels. Do not produce TikTok, YouTube, Pinterest, X,
Threads, Facebook, or Reddit content unless explicitly asked.

## Conventions

- Drafts go in `drafts/` as `YYYY-MM-DD-platform-slug.md`
- Once posted, move to `published/` and append the post URL at the top
- Images and video live in `assets/`
- `calendar.md` holds the recurring posting rhythm

## Skill routing

| Job | Skill |
|---|---|
| Plan a week/month | `batch-content-plan`, `content-calendar` |
| LinkedIn post | `linkedin-post-writer` (strategy-native) or `li-post-writer` (voice-file method) |
| Sharpen a LinkedIn draft | `li-post-formatter`, `li-post-scorer` |
| Reel / short video | `reels-script`, `short-form-video-script` |
| Carousel | `carousel-writer` or `li-gemini-carousel` |
| Opening line | `hook-writer`, `li-hook-generator` |
| Visuals | `image-prompt`, `nano-banana`, `canva` |
| Turn one post into many | `cross-platform-repurposing` |
| Review performance | `analytics-and-reporting`, `viral-reverse-engineering` |
