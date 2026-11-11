# StandRight marketing plan

Dated 10 November 2026 (America/Vancouver). This file records the latest agreed marketing strategy, existing drafts, what has already happened, and what is still open. It is not itself an approval to post, publish, deploy or spend.

This site repository is public (GitHub Pages). This note contains only marketing strategy and public copy.

The older listing and post drafts on the marketing Page predate Chip's later decision to lead with private Android habit building and to avoid posture claims such as "taller" or "more confident." Those Page drafts are kept here as they stood, with that caveat.

Marketing plan Page (checked 4 November 2026; nothing on it was posted or submitted): https://cursor.com/canvas/store-02eb8cb9-dbdd-43fc-9a2b-e5e4eb0aae12/761d2e4f-c03d-46e0-9a60-b8d24d430087

## Strategy and constraints

- Time: about one hour a week.
- Money: keep initial spend under US$100; treat any paid work as a separate decision. The 4 November Page also sketches a later paid test (Google App campaign first, posture micro-creators second), capped at about €300–500, only after screenshots and a handful of ratings, and only if cost per install stays around €1 or below. That paid section has not been approved as a current task.
- Positioning Chip chose: lead with private Android habit building. Avoid claims about diagnosing, preventing or treating a condition, implications that the app measures body posture, and posture claims such as "taller" or "more confident."
- Public copy: use Chip's own draft as the basis; leave the finishing pass to him. He owns positioning, prioritisation, design and spending; present options with trade-offs and wait for his view.
- Exclusions: Product Hunt is out. He will write and submit any Show HN himself.
- Standing process: first pass read-only; outline proposed repo changes in two or three bullets and wait for approval; get separate approval before publishing, posting, deploying or spending.
- He plans to charge for StandRight later (noted 5 November 2026). The app is still free, with no ads and no in-app purchases.

## Decisions Chip made

- Restructure the site so it explains the app first.
- First marketing hour, after the release: the Play listing plus an r/droidappshowcase post (r/androidapps sends developer self-promo there).
- He will capture screenshots on his phone.
- Release the latest app changes first, then do marketing (10 November).
- He wanted to review 1.4.4 on an APK with an exact test list, then do Play Console. Sideloading failed because his Privy-built Odyss blocker blocks install and USB debugging. An internal-testing plan was proposed (signed 1.4.4 / versionCode 10 AAB to the internal track, only him as tester) and is still waiting for his go-ahead and for where Play Console is signed in.
- Marketing still waits on his 3–5 bullets, confirmation that his Reddit account is eligible (24+ hours old, 2+ karma), and an explicit "approved."

## Content that exists

### Paste-ready listing copy on the Page

This copy is older than the habit-first, no-posture-claims decision, and it still leads on posture:

- Tagline: "Posture check-ins each time you unlock your phone"
- Short: "A free Android posture habit app: one tap on unlock, upright or slouched, plus a soft screen-edge glow when you tip back. No account, no ads, no analytics."
- Long: "StandRight builds a posture habit with almost no effort. Each time you unlock your phone it asks one question, upright or slouched, answered in one tap. A 4-week calendar and streaks show how you're doing, and Straight-up mode adds a soft glow on the screen edge when you tip the phone back too far. Set a schedule or pause it so it never nags. No account, no ads, no analytics, and you can export your data as CSV. Not a medical device."
- Tags: Health & Fitness, Productivity, Android, Posture, Habit tracker, Privacy

### Ready-to-post drafts on the Page

Show HN title: "Show HN: StandRight – an Android posture check-in each time you unlock your phone"

URL: https://play.google.com/store/apps/details?id=dev.cip.standright

First comment: "I kept catching myself hunched over my phone. StandRight asks one question when you unlock, upright or slouched, in one tap, and shows a 4-week calendar and streaks. Straight-up mode puts a soft glow on the screen edge when you tip the phone back past an angle. No account, no ads, no analytics, CSV export, and it's not a medical device. Schedules and pause keep it from nagging. Curious whether the check-in feels helpful or annoying after a few days."

r/droidappshowcase title: "I made a free posture app that checks in when you unlock your phone. No account, no ads"

Body: "StandRight asks \"upright or slouched?\" with one tap when you unlock, then shows your 4-week calendar and streaks. Straight-up mode adds a soft glow on the screen edge when you tip the phone back too far. You can schedule it or pause it. No account, no ads, no analytics; you can export your data as CSV. Free on Google Play: https://play.google.com/store/apps/details?id=dev.cip.standright. I'm the developer and would love feedback on how often the check-in should appear. [Add 2-3 screenshots]"

The Page also lists ASO (problem keyword in the 30-character title and short description; screenshots of the unlock check-in and screen-edge glow), an X build-in-public 10-second Straight-up clip, and a six-week calendar that put Peerlist, r/droidappshowcase, ASO and a Show HN in late November. That calendar has not been adopted as Chip's current plan; his later constraints supersede it.

### Listing copy in the app repo

The more complete Play listing draft lives in the StandRight app repository at `docs/store/listing.md` (titled "Play Store listing — v1.4.0"; last related docs commit 3 October 2026). It has not obviously been revised for 1.4.4. Excerpt:

- Title (max 30): `StandRight: Posture Habit` (25)
- Short (max 80): `Gentle posture check-ins every time you unlock. No account, no cloud, no ads.` (77)
- It states that the phone angle "stands in for where your head is; it does not measure you," and includes the medical disclaimer: "StandRight is a habit-building reminder tool, not a medical device. It doesn't diagnose, treat, or prevent any condition."

`docs/play-launch-plan.md` in the app repo is an older Play publishing plan (v1.4, addendum 26 August 2026). The app is already live, and Crashlytics was deferred, so treat that document as historical, not the current marketing strategy.

### Site copy in this repository

On `origin/main` as of 10 November 2026 (commit `dc7734d`, from [PR #1](https://github.com/cipshadow/standright-site/pull/1), merged 4 November 2026):

- Title: "StandRight – Posture habit for Android"
- Description: "Gentle posture check-ins for Android, every time you unlock. No account, no cloud, no ads."
- H1 is still "Sit taller, gently." That conflicts with Chip's later ban on "taller" style claims.
- The earlier "Coming soon to Google Play" pill has already been replaced with a "Get it on Google Play" badge linking to https://play.google.com/store/apps/details?id=dev.cip.standright.
- The same PR added `sitemap.xml`, `robots.txt`, and Open Graph tags.

### Unknowns

- X tips Chip shared in the 10 November marketing conversation: the exact text was not recovered when this file was written.
- His 3–5 marketing bullets: not provided.

## What has been done or launched

- StandRight is live on Google Play: https://play.google.com/store/apps/details?id=dev.cip.standright. A Page check on 4 November 2026 listed it as "StandRight: Posture Habit," developer ChipChopInc, 10+ downloads, updated 28 October 2026. Live Play metadata was not re-opened on 10 November.
- App work for 1.4.4 (versionCode 10) is merged to the app repo `main` via [PR #24](https://github.com/cipshadow/StandRight/pull/24), merge commit `8a29a26`, merged at 4:13 PM PT (America/Vancouver) on 10 November 2026 (GitHub `2026-11-11T00:13:51Z`). This is the code release, not a Play upload.
- A 1.4.3 test APK was built for review; Chip could not sideload it because of the Odyss/Privy blocker. 1.4.4 has not been built for Play.
- Nothing has been posted to Reddit, Show HN, X, Peerlist, AlternativeTo, or other directories. The Page's submission tracker still read "Not submitted" as of 4 November; no later submission was found.
- Two routines were noted as paused in the 10 November working context: "Daily app launch submission" and "Demoku Uneed launch-day reminder." That status was not re-checked against the routines tool when this file was written.

## What is open or waiting on Chip

- Approve (or change) the internal-testing plan, and say whether Play Console is signed in on his Mac or needs a computer handoff.
- After he reviews the Play-delivered build: production release notes, then a yes before publishing.
- Marketing after the release: his 3–5 bullets, Reddit eligibility, and "approved" before any listing edit, r/droidappshowcase post, or other publish.
- Site work he already chose (explain the app first; drop "Sit taller") has not been started, and still needs a plan plus approval. The Play badge and crawl files are already on `main`.
- The app-repo listing draft and the Page drafts may need a finishing pass so they lead on private habit building and do not use "taller"-style claims.
- Show HN remains optional and is his to write and submit.
- Paid spend remains a separate later decision.
