# TikTok & Shorts Video Downloader Bot

🔹 Отправь боту ссылку на TikTok или YouTube Shorts — он скинет тебе видео без водяных знаков.

## Развёртывание на Render
1. Зарегистрируйся на https://render.com
2. Создай новый Web Service → "Deploy from GitHub" или ZIP
3. Укажи:
   - Build Command: `pip install -r requirements.txt`
   - Start Command: `python main.py`
   - Environment Variable: `BOT_TOKEN=твой_токен`