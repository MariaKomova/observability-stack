# Observability Stack

Компоненты:
- Grafana (3000): admin/admin123
- Prometheus (9090): сбор метрик
- Loki (3100): логи
- Promtail: сбор логов

Запуск:
docker-compose -f docker-compose.observability.yml up -d

Настройка Grafana:
1. http://localhost:3000
2. admin/admin123
3. Добавьте Prometheus (http://prometheus:9090)
