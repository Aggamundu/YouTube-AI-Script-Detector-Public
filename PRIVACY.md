# Privacy Policy

**YouTube AI Script Detector** · Effective November 26, 2026

This extension estimates whether a YouTube video's script was written by AI. This policy explains what data it uses and why.

## What the extension sends

When you open a YouTube video with the extension switched on, it sends the following to its scoring server (`api.aiscriptcheck.org`, hosted on Cloudflare; version 1.0.0 used `ai-script-check.ryancepeda2.workers.dev`, the same server):

- **The video's ID**, the **text of its transcript** (captions), and the **caption type and language**, which are needed to score the video.
- **A random install ID**, created when the extension is installed. It is not linked to your name, Google account or YouTube account, and is used only to apply the daily check limit.

Your IP address is seen by the server as part of any internet request, and is used only to apply the daily check limit.

The extension does not read your browsing history, your YouTube account details or your comments, and it sends nothing from sites other than YouTube video pages.

## What the server keeps

- **Results:** the score for each video is cached for up to 90 days, so the same video is not scored twice. The cache is keyed by the video ID and a one-way hash of the transcript. It stores the result, not the transcript.
- **Daily check counts:** a count of checks for each install ID and each IP address, deleted automatically after 2 days.
- **Transcripts** are scored and then discarded. They are not stored or logged.

Cloudflare, which hosts the server, may keep standard technical logs under its own [privacy policy](https://www.cloudflare.com/privacypolicy/).

## What the extension stores in your browser

- Your on/off setting and the install ID.
- Results for up to 500 recently checked videos, kept for up to 30 days.

This data stays in your browser. Uninstalling the extension deletes it.

## What we don't do

- We do not sell your data or transfer it to third parties, except to Cloudflare, which hosts the scoring server and handles data only to provide this service.
- We do not use your data for advertising, profiling or credit decisions.
- We do not use transcripts sent by the extension to train the AI detector.

This extension's use of data complies with the [Chrome Web Store User Data Policy](https://developer.chrome.com/docs/webstore/program-policies/user-data-faq), including the Limited Use requirements.

## Changes

If this policy changes, the new version will be posted here with a new effective date.

## Contact

Questions: ryancepeda2@gmail.com
