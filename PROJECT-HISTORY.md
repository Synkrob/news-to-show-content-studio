# News to Show — Project History

## Purpose

News to Show is a tablet-first content workflow for turning daily AI, robotics, policy, schools, and technology news into a short spoken show and platform-ready social drafts.

The operating goal is simple: review a small research pool, choose the stories that fit the show, read a clear script, add a recording, review the light edit, and approve the publishing package.

## Workflow agreed so far

1. Research gathers up to **10 stories**.
2. The host normally selects up to **7 stories** for the show.
3. The remaining stories stay available as backups.
4. Each selected story has a short title, summary, why-it-matters explanation, easy-to-read copy, and a one-line preview.
5. The host records the show on a phone or tablet.
6. The host handles lighting, color, tone, trimming, and other personal creative choices.
7. The system prepares the remaining light-edit package, captions, and platform drafts.
8. The host reviews and approves before publishing.

## Prototype completed

- AiX HUB visual theme applied to the interface.
- Responsive layout for phone and tablet use.
- Compact stage navigation: Research, Selected, Script, Edited, Published.
- Local browser state for testing the workflow.
- Recording upload control for the selected story.
- Simulated light-edit progress.
- Draft copy areas for YouTube, Instagram, TikTok, and Facebook.
- Final approval gate before a future scheduler connection.
- Research service code that reads up to ten approved RSS sources, filters by topic and time window, and removes duplicate headlines.

## Approved research sources

The first source set includes Microsoft AI, MIT Technology Review, The Verge AI, Google News, CNN, Fox News, TechCrunch AI, Ars Technica, NASA technology/robotics, and the U.S. Department of Education.

The source list is a starting point. It can be adjusted when a feed becomes unreliable, too repetitive, or outside the editorial focus.

## Current repository and preview

Repository: https://github.com/Synkrob/news-to-show-content-studio

Live preview: https://synkrob.github.io/news-to-show-content-studio/

GitHub Pages currently hosts the interface. The research server is separate because GitHub Pages is a static host and cannot run the Node service, process uploads, store private keys, or perform video/audio work.

## What is still simulated

- The live cloud research endpoint is not connected to GitHub Pages yet.
- Audio briefing generation is not connected.
- Caption generation and video processing are represented by the prototype flow.
- Cloud file storage is not connected.
- Social publishing is still an approval-and-draft step rather than an automatic publish action.

## Recommended stopping point for this phase

This phase is complete when the GitHub preview shows the ten-story research limit, the seven-story show limit, the compact workflow stages, and this project history file. That gives the host a stable artifact to test on a tablet before investing in cloud services.

## Next build phase

1. Deploy the research endpoint to a small cloud service.
2. Connect the GitHub Pages interface to that endpoint.
3. Save briefings and selected stories in cloud storage.
4. Add speech/audio generation after the written briefing is reliable.
5. Add captions and the hybrid video finishing step.
6. Connect a publishing scheduler with the host's final approval required.

The design deliberately keeps the host in control of story selection, voice, creative look, and final publishing approval.
