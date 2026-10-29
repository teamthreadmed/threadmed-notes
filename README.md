# Thread Notes

Source for **notes.threadmed.org**. Every change you commit to `main` rebuilds and publishes the site in about two minutes (watch the **Actions** tab).

## Editing (no software needed)
1. Open a note under `content/` on github.com.
2. Click the pencil icon, edit, then **Commit changes**.
3. New note: in `content/`, click **Add file → Create new file**, name it `Something.md`.

## What goes public
A note is published **only** if its frontmatter has `publish: true`. Everything else stays out of the website.

**This repository is public.** Anyone can read unpublished notes on github.com. Never put patient information, or anything you would not want seen, in this repo. Truly private notes live in Google Drive (Thread Notes folder).

## Note format
```yaml
---
publish: false          # true = on the website
type: drug              # home, condition, algorithm, drug-class, drug
up: "[[Bisphosphonates]]"
source: "FDA label; AACE/ACE 2020 PMO"
version_date: 2026-10-29
evidence: "verify"      # change to your sign-off once reviewed
review_by: 2027-04-30
---
```
Link notes with `[[Note name]]`. Tables that list notes automatically use ```base blocks (see `content/Bone/Osteoporosis.md`).

## Site settings
Title, colors and fonts: `quartz.config.yaml`. Built with [Quartz](https://quartz.jzhao.xyz).
