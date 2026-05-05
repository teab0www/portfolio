# Portfolio

PM by trade, builder by habit. [LinkedIn](https://linkedin.com/in/tlefaucheur)

## Browser Extensions

**[x-auto-poster](https://github.com/teab0www/x-auto-poster)**
X's API is expensive and rate-limited -- browser automation is neither.
- Schedules and auto-posts content on X by driving the compose UI directly, no API key, no OAuth
- Human-like input timing to avoid bot detection, Supabase as the default data source
- Stack: Chrome Extension (MV3), JavaScript

**[meet-mute-chrome](https://github.com/teab0www/meet-mute-chrome)** -- [Chrome Web Store](https://chromewebstore.google.com/detail/google-meet-mute-shortcut/libibdbacjghlaggmdcgajpbdnbmnmgp)
Unmuting in Google Meet requires switching to the right tab, every single time.
- Global hotkey to mute/unmute from any tab, without switching to the meeting window
- Works across multiple simultaneous meetings, fully customizable shortcut
- Stack: Chrome Extension (MV3), JavaScript

**tab-jumper**
Switching between frequently used tabs by clicking is slow.
- Keyboard shortcuts to jump to specific tabs instantly
- Smart URL matching handles dynamic URLs for Google Docs, Gmail, Jira, and Calendar
- Stack: Chrome Extension (MV3), JavaScript

## AI / Data Tools

**diablo** -- [diablo132.vercel.app](https://diablo132.vercel.app)
The Lamborghini Diablo (Italian sports car) has a strong community with decades of technical knowledge buried in forum threads and hard to search.
- Ask like you'd ask a mechanic: "clutch slipping at low speed" finds threads about gearbox wear, not just posts containing those exact words
- 3,300 threads summarized by an LLM, embedded and ranked by semantic similarity
- Stack: OpenAI embeddings, Supabase pgvector, Next.js

**[dredgio](https://github.com/teab0www/dredgio)** -- [dredgio.vercel.app](https://dredgio.vercel.app)
Tracking what people say about a topic across Reddit, Hacker News, and Google News is manual and slow.
- Define a topic, get a structured intelligence report with signals, themes, and sentiment
- Aggregates and summarizes across sources in one shot
- Stack: Python FastAPI, React, DeepSeek, Railway + Vercel

**voice-finance-tracking**
Logging expenses on the go is friction -- opening an app, tapping fields, selecting categories.
- Speak naturally ("12 euros on lunch"), GPT-4o-mini parses it into structured fields
- Entries land directly in Google Sheets via Service Account, categories driven by a config tab
- Stack: Vanilla JS, Web Speech API, OpenAI GPT-4o-mini, Google Sheets API
