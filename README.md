# Прайм Принт сайт (Jekyll)

## Локално стартиране
1) Ruby зависимости:
```bash
bundle install
```
2) CSS (Tailwind CLI):
```bash
npm install
npm run build:css      # еднократно изграждане
npm run dev:css        # watch режим в отделен терминал
```
3) Стартирайте Jekyll:
```bash
bundle exec jekyll serve
```
Отворете http://127.0.0.1:4000

## Скриптове
- `npm run build:css` — генерира `assets/tailwind.css` (включва preflight и utilities).
- `npm run dev:css` — watch режим за Tailwind.

Забележка: Основните стилове са в `assets/custom.css`; Tailwind е добавен за бъдещи компоненти и utility класове.
