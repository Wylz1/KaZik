# KaZik — запуск

1. @BotFather → /newbot → получи токен.
2. Выложи `index.html` на любой HTTPS-хостинг (GitHub Pages, Netlify, Vercel, Cloudflare Pages).
3. Запусти бота:
   pip install -r requirements.txt
   export BOT_TOKEN="123:ABC"
   export WEBAPP_URL="https://твой-сайт/index.html"
   python bot.py
(Windows: `set BOT_TOKEN=...`, `set WEBAPP_URL=...`)
4. Напиши боту /start и нажми «Открыть KaZik».
