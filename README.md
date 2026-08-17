# Launch House — Free Training Page

Minimal free-training page.

## Replace these two values in `index.html`

1. `REPLACE_WITH_VIDEO_URL.mp4`
   - Put your actual training video URL here.
   - Native MP4 hosting is the simplest option for the current implementation.

2. `REPLACE_WITH_197_LANDING_PAGE_URL`
   - Put the URL of your ₹197 `Launch a Startup in 2 Hours` landing page here.

## Behaviour

- The page intentionally contains almost no sales copy.
- The CTA starts hidden.
- It appears after 30 seconds of actual video playback.
- Pauses do not count.
- Simple seeking does not count toward the 30-second threshold.
- Once unlocked, the CTA stays visible.
- Mobile responsive.
- Can be deployed directly to Vercel as a static site.

## Optional

You can add a poster image to the video tag:

`poster="assets/video-poster.jpg"`
