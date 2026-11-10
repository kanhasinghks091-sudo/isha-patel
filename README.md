# Isha Patel — VIP Access

A single-page landing site for the Isha Patel VIP Telegram channel. It shows a branded card with the channel profile, stats, and a "Join Telegram Now" button, and automatically redirects visitors to the Telegram invite after a 15-second countdown.

## Technologies

- Plain HTML, CSS, and vanilla JavaScript (no build step)
- Google Fonts (Cinzel, Plus Jakarta Sans)
- Hosted on Netlify

## Running locally

Open `public/index.html` in a browser, or run `netlify dev` from the project root.

## Editing

- Telegram invite link: update both the button `href` and `TELEGRAM_URL` in the script in `public/index.html`.
- Countdown length: change `TOTAL_SECONDS` (and the initial `15s` label).
