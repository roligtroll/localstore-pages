# localstore-pages

Static pages for the LocalStore Telegram bot (version 1.0). Telegram opens them as Web Apps, and they need an HTTPS address.

Files are immutable per version: a change ships as a new file (`scan-1.1.html`), never an edit of `scan-1.0.html`. The bot checks each page's hash before it uses it.

- `scan-1.0.html`, `show-code-1.0.html`, `form-1.0.html`, `pick-items-1.0.html`, `pick-slot-1.0.html`, `sign-1.0.html`

No data is stored here. The pages hand their result back to the bot through Telegram and send nothing to any other server.
