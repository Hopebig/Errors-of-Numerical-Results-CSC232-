bgdreambot/
│
├── main.py              — bot startup, handlers, routing only
├── memory.py            — existing, keep as is
├── config.py            — all env vars, model names, URLs in one place
├── prompts.py           — all system prompts, viral prompt, score prompt
├── agnes.py             — all Agnes API calls (chat, image, video)
├── vision.py            — Nemotron vision calls
├── search.py            — Serper web search
├── audits.py            — X and YouTube audit logic
├── content.py           — viral generator, scorecard, AI editor, repurpose
├── intelligence.py      — trend radar, opportunity finder, audience DNA
└── handlers/
    ├── chat.py          — normal_chat, edited_message
    ├── media.py         — photo_handler, video_handler, audio_handler
    ├── commands.py      — start, help, forget, image, video, viral
    └── router.py        — all intent detection functions
