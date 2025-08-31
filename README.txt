ai.bodyartweb.online – пакет файлов для GitHub Pages

Что внутри:
- ai.txt — разрешение для LLM-ботов (GPTBot, ClaudeBot, PerplexityBot, Google-Extended, CCBot) + ссылки на sitemaps.
- sitemap-images.xml — карта изображений для Google Images.
- index.html — техстраница со ссылками (можно не менять).
- CNAME — файл с текстом `ai.bodyartweb.online` (для привязки домена в GitHub Pages).

Быстрый деплой на GitHub Pages:
1) Создайте публичный репозиторий, например `ai-bodyartweb-online`.
2) Загрузите файлы из архива в корень репозитория.
3) Settings → Pages:
   - Source: Deploy from branch
   - Branch: main / root
4) Дождитесь адреса вида `https://USERNAME.github.io/REPO/`.
5) В Custom domain укажите `ai.bodyartweb.online` и сохраните.
6) В GoDaddy → DNS добавьте CNAME:
   - Host/Имя: ai
   - Points to/Значение: USERNAME.github.io
   - TTL: 1 hour
7) Проверьте `https://ai.bodyartweb.online/ai.txt`
