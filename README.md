# Тестовое приложение на Django

## Расхождения с оригинальным мануалом

### timezone.now() vs. timezone.localtime()
Вместо timezone.now() надо использовать timezone.localtime() - первая возвращает время в часовом поясе UTC, игнорируя TIME_ZONE в settings.py
 