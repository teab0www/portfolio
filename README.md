# Portfolio

PM by trade, builder by habit.  
[LinkedIn](https://linkedin.com/in/tlefaucheur)

## Browser Extensions

**>> [x-auto-poster](https://github.com/teab0www/x-auto-poster)**  
Chrome addon to schedule and automatically post on X via browser automation (no API).
- Human-like input timing to avoid bot detection
- Supabase as the default data source, swappable
- Stack: Chrome Extension (MV3), JavaScript

**>> [meet-mute-chrome](https://github.com/teab0www/meet-mute-chrome)**  
[Chrome Web Store](https://chromewebstore.google.com/detail/google-meet-mute-shortcut/libibdbacjghlaggmdcgajpbdnbmnmgp)  
Chrome addon to control Google Meet mute/unmute from a global keyboard shortcut.
- Works from any tab, without switching to the meeting window
- Supports multiple simultaneous meetings, fully customizable shortcut
- Stack: Chrome Extension (MV3), JavaScript

**>> tab-jumper**  
Chrome addon to jump to specific tabs via keyboard shortcuts.
- Smart URL matching handles dynamic URLs for Google Docs, Gmail, Jira, and Calendar
- Stack: Chrome Extension (MV3), JavaScript

## AI / Data Tools

**>> diablo**  
[diablo132.vercel.app](https://diablo132.vercel.app)  
The Lamborghini Diablo (Italian sports car) has a strong community with decades of technical knowledge buried in forum threads and hard to search.
- Ask like you'd ask a mechanic: "clutch slipping at low speed" finds threads about gearbox wear, not just posts containing those exact words
- 3,300 threads summarized by an LLM, embedded and ranked by semantic similarity
- Stack: OpenAI embeddings, Supabase pgvector, Next.js

**>> [dredgio](https://github.com/teab0www/dredgio)**  
[dredgio.vercel.app](https://dredgio.vercel.app)  
Market intelligence tool that aggregates and summarizes any topic across Reddit, Hacker News, and Google News.
- Structured report with signals, themes, and sentiment in one shot
- Stack: Python FastAPI, React, DeepSeek, Railway + Vercel

**>> voice-finance-tracking**  
Personal expense tracker: speak naturally, entries land directly in Google Sheets.
- GPT-4o-mini parses voice input into structured fields (amount, currency, category)
- Categories driven by a config tab in the Sheet, no code changes needed
- Stack: Vanilla JS, Web Speech API, OpenAI GPT-4o-mini, Google Sheets API
