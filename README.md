# Suumer US Local Events: weekly snapshot

Every upcoming public event listed on [Suumer](https://suumer.com) on 2026-11-26: 895,872 dated events at 156,973 places in 15,017 towns across 53 states and territories, through 2029-11-26. Trivia nights, concerts, comedy, story times, markets, plays, classes and more.

Suumer is a free guide to what's on near you in the United States. Each listing is checked against the venue's or organizer's own public page before it goes live. A fresh copy comes out every week.

## Download

Newest files: [Releases, latest](https://github.com/suumer-app/suumer-us-events/releases/latest) (`suumer-events.csv.gz`, `suumer-events.jsonl.gz`). This week's: [snapshot-2026-11-26](https://github.com/suumer-app/suumer-us-events/releases/tag/snapshot-2026-11-26).

## Files

- `suumer-events.csv.gz`: one row per event date, comma-separated, UTF-8.
- `suumer-events.jsonl.gz`: the same rows, one JSON object per line.

| Column | What it holds |
|---|---|
| `id` | Suumer's id for this event date |
| `title` | The event's name |
| `kind` / `kind_label` | Suumer's category, as a key (`general_trivia`) and in words ("General-knowledge trivia") |
| `start_date` | Local date, YYYY-MM-DD |
| `start_time` | Local start time, HH:MM, empty when the source gives none |
| `all_day` | true for all-day events |
| `time_zone` | The venue's time zone |
| `status` | `scheduled`, or `cancelled` / `postponed` when the source says so |
| `venue_name` | Where it happens |
| `town` / `state` | The venue's town and two-letter state |
| `suumer_url` | The event's page on suumer.com: times, address, map and the link to its source |

Descriptions, pictures, addresses and organizer details are left out on purpose: they live on each event's Suumer page and its source.

## Licence

[Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/), granted in [Suumer's data terms](https://suumer.com/data-terms). Share it, study it, build on it. Name Suumer as the source and link [suumer.com](https://suumer.com), or each event's `suumer_url`.

Events change. Check the event's page before you go.

## Fresher than weekly

Suumer's free event feed answers by town and date, no key needed: [suumer.com/api](https://suumer.com/api). Questions: hello@suumer.com.
