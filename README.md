# Portfolio

[LinkedIn](https://linkedin.com/in/tlefaucheur)

---

## Browser Extensions

### x-auto-poster
Chrome extension that schedules and auto-posts content on X.com by driving the compose UI directly — no API key, no OAuth. Posts live in a database (Supabase by default); the extension registers Chrome alarms and fires them at the right time using human-like input to avoid bot detection.

### meet-mute-chrome
Global mute/unmute hotkey for Google Meet. Works from any tab without switching to the meeting window. Supports multiple simultaneous meetings and a fully customizable shortcut. Available on the [Chrome Web Store](https://chromewebstore.google.com/detail/google-meet-mute-shortcut/libibdbacjghlaggmdcgajpbdnbmnmgp).

### tab-jumper
Keyboard shortcuts to jump to specific browser tabs instantly. Smart URL matching handles dynamic URLs for Google Docs, Gmail, Jira, and Calendar so the shortcut keeps working regardless of which document or calendar view is open.

---

## AI / Data Tools

### diablo
Semantic search over ~40,000 Lamborghini Diablo forum posts. A Chrome extension scraped 3,300 threads from a long-running owner community; an LLM summarized each one; summaries were embedded with `text-embedding-3-small` and stored in Supabase with pgvector. Search by plain-English question, get ranked results in milliseconds. Live at [diablo132.vercel.app](https://diablo132.vercel.app).

### dredgio
Market monitoring tool. Define a topic, get a structured intelligence report aggregated from Reddit, Hacker News, and Google News. FastAPI backend on Railway, React frontend on Vercel, DeepSeek as the LLM. Live at [dredgio.vercel.app](https://dredgio.vercel.app).

### voice-finance-tracking
PWA for tracking personal expenses by voice. Speak naturally ("12 euros on lunch"), GPT-4o-mini parses it into structured fields, and the entry lands in Google Sheets via Service Account. Categories are driven by a config tab in the same Sheet — no code changes needed to add new ones. Built for daily mobile use on Android Chrome.
