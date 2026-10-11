# TryAIToday Studio — Colab Notebook

The GPU engine for **TryAIToday Studio**: Text‑to‑Speech (Chatterbox), Speech‑to‑Text
(Whisper), and Image/Video Upscaling (Real‑ESRGAN) — served over a Cloudflare tunnel
to the autoeditor web app.

## Open in Colab (always the latest)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/codewithsiddique-04/tryaitoday-studio-notebook/blob/main/TryAIToday_Studio.ipynb)

Direct link:

```
https://colab.research.google.com/github/codewithsiddique-04/tryaitoday-studio-notebook/blob/main/TryAIToday_Studio.ipynb
```

Because Colab loads straight from this repo, pushing an update here means every user
gets the newest notebook the next time they open that link — nothing to re‑share.

## How to run

1. **Runtime → Change runtime type → GPU (T4)**, then **Runtime → Run all**.
2. Approve the Google sign‑in + Drive access when prompted.
3. When the last cell prints the engine URL, your session is live and registered —
   open **autoeditor** and click **Connect engine** (same Google account).

## Notes

- Sign into Colab with the **same Google account** you use in autoeditor / the
  Flow Automator extension — the engine is registered under that account.
- Each run gets a fresh tunnel URL; the notebook re‑registers it automatically.
