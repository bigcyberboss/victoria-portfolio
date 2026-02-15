# Портфолио Victoria Strelkova - Проектные заметки

## Домен и хостинг
- Домен: vstrelkova.art (куплен на reg.ru)
- Хостинг: GitHub Pages (github.com/bigcyberboss/victoria-portfolio)
- HTTPS: включен через GitHub Pages
- DNS: A записи на GitHub IPs + CNAME www -> bigcyberboss.github.io

## Что сделано (февраль 2026)

### Лендинг (index.html)
- Одностраничный лендинг, двуязычный (RU/EN)
- Тёмная тема с золотыми акцентами
- 12 проектов из Behance с lightbox галереей
- Секции: Hero, About, Services, Portfolio, Process, Contact

### SEO
- JSON-LD structured data (Person, ProfessionalService, ItemList, BreadcrumbList)
- Гео-привязка к Севастополю/Крыму для Яндекса
- sitemap.xml с image sitemap
- robots.txt
- Open Graph + Twitter Card мета-теги
- Ключевые слова: "дизайнер интерьера Крым", "3D визуализация Севастополь"

### Безопасность
- noopener noreferrer на внешних ссылках
- Security headers (Referrer-Policy, X-Content-Type-Options, Permissions-Policy)
- Нет форм, нет бэкенда - минимальная поверхность атаки
- GitHub Pages = Fastly CDN (DDoS protection)

### Оптимизация
- Safari webkit prefixes
- Passive scroll listeners, requestAnimationFrame
- preconnect к CDN, will-change для анимаций
- 4 responsive брейкпоинта (480px, 768px, 1024px, 1920px+)
- prefers-reduced-motion для accessibility
- Touch swipe в lightbox

### UI-фичи
- Прогресс-бар прокрутки вдоль шапки
- Кнопка "наверх" слева
- Мобильное бургер-меню

## TODO
- [ ] Зарегистрировать в Яндекс.Вебмастер (webmaster.yandex.ru)
- [ ] Вставить yandex-verification код в index.html
- [ ] Зарегистрировать в Google Search Console
- [ ] Отправить sitemap в оба сервиса
- [ ] Фидбек от Виктории
