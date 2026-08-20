# AI Quality Dashboard

Дашборд качества AI налогового ассистента для МСБ. Прототип: single-file HTML, все расчёты client-side.

- Live: https://ai-quality-dashboard-teal.vercel.app
- Метрики: время ответа (avg / median / p90) по дням, качество ответов (правильные / частично / вода / ошибка), дефекты по таксономии, категории вопросов, топ вопросов
- Загрузка своих данных: CSV / JSON / XLSX, drag-and-drop; колонки на русском или английском. Обязательны только «вопрос» и «время_ответа»
- Пример данных: [sample-data.csv](sample-data.csv) (632 диалога за 30 дней)
- PRD production-версии: [docs/PRD-ai-quality-dashboard.md](docs/PRD-ai-quality-dashboard.md)

Запуск локально: открыть `index.html` в браузере (для XLSX нужен интернет, парсер грузится с CDN).
