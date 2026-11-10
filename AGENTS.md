# AGENTS.md

## Architecture
Static single-file site. `public/index.html` contains all markup, styles, and script. `netlify.toml` publishes the `public/` directory with no build command.

## Conventions
- Keep everything self-contained in `public/index.html` unless the site grows.
- The Telegram invite URL appears twice (button `href` and `TELEGRAM_URL` constant); keep them in sync.
- The countdown starts at `TOTAL_SECONDS`; the initial `15s` label in the markup should match it.
- The avatar is loaded from Unsplash; swap in a local image under `public/` if a real profile photo is provided.
