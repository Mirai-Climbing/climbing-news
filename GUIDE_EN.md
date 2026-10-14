# Daily English edition (instructions for the AI)

This repository is a climbing news site on GitHub Pages. Every morning (US Eastern time), follow these steps to write one day's English summary, add one file under `en/_posts/`, and push it to `main`. The Japanese edition (`_posts/`, `GUIDE.md`) is written separately; do not touch it.

## 1. Gather
Find stories published after the previous English summary (the newest file in `en/_posts/`). **Look for US stories first**, then the rest of the world, then big stories from Japan. Large foreign sites have many stories, so if you start with them you tend to stop there.

1. Open the US sources below one by one and check their news pages directly (search often misses them).
2. Search the web, newest first. Examples: "USA Climbing results", "climbing gym opening", "climbing gym closing", "crag closure", "rebolting", "Access Fund", "first ascent", "climbing news".
3. Then check world and Japanese sources.

A US story published up to 7 days before the previous summary may still be included if it has not been covered yet (US gym and access news is easy to find late). World and Japanese stories must be newer than the previous summary.

| Section | Where to look (examples) |
|---|---|
| Competitions | USA Climbing (usaclimbing.org), World Climbing (worldclimbing.com), collegiate and regional series, Wikipedia "2026 World Climbing Series" |
| Crags & access | Access Fund (accessfund.org) news and action alerts, local climbing organizations (LCOs), American Alpine Club (americanalpineclub.org), National Park Service closures |
| Gyms | Climbing Business Journal (climbingbusinessjournal.com) openings and closings, local news |
| Outdoor ascents | Climbing (climbing.com), Gripped (gripped.com), Rock and Ice / Outside, UKClimbing (ukclimbing.com), PlanetMountain (planetmountain.com), 8a.nu |
| Gear | Manufacturer announcements, Climbing and Gripped gear news |
| Events | Film tours (Reel Rock), festivals, clinics, meetups |
| Japan | Japan Mountaineering & Sport Climbing Association (jma-climbing.org), CLIMBERS (climbers-web.jp). Only the biggest stories, summarized in English |

## 2. Check (do not include a story unless every item holds)
- You opened the original article (an official announcement or a news site) yourself and confirmed the content and the date.
- It has not appeared in earlier English summaries.
- It is not a rumor, not based only on a personal social media post, and its origin is clear.
- It does not reveal the location of a crag that is not open to the public.
- It does not name private individuals. Athletes, professional climbers, and people featured in the article are fine.

## 3. Write
- **Never copy the article's text or photos.** Summarize the point in your own words in 1–2 sentences and link to the original. Do not reuse the headline as is.
- Keep numbers (rankings, records, dates) exactly as in the original.
- Write in plain, simple English. Keep grades as the source writes them (V14, 5.15a, 8c+). For Japanese stories, write names in English and mention the original language after the link, like "(Japanese)".
- Use the date of the original article (local date).
- Put a blank line between the headline, the description, and the link (otherwise they run into one line).
- Use these section headings: "## Competitions", "## Crags & Access", "## Outdoor Ascents", "## Gyms", "## Gear", "## Events". **Leave out sections with no stories** (do not write "nothing found").
- Inside each section, put US stories first. For the title (the biggest story), choose a US story if there is a big one.
- If there is no story at all, do not create a file.

File name: `en/_posts/YYYY-MM-DD-news.md` (today's date in US Eastern time)

```
---
layout: post
title: "Climbing news, Month D: (one or two biggest stories)"
---

## Competitions

**(one-sentence headline)** (date it happened)

(1–2 sentence description)

[Source name](URL of the original article)

---
This summary is written by AI. If you spot a mistake, please tell us on [GitHub Issues](https://github.com/Mirai-Climbing/climbing-news/issues).
```

## 4. Publish
- Add only the one file under `en/_posts/`. Do not change other files.
- Commit message: "News for Month D (English)". Push to `main`.
