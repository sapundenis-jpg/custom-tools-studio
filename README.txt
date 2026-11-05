Многостраничный сайт + Supabase

Supabase project:
https://bpdqosfgxqawbzljafgb.supabase.co

Что уже подключено:
- projects.html загружает опубликованные строки из public.projects
- формы на index.html и contacts.html создают строки public.contact_requests
- используется publishable key; доступ ограничен RLS-политиками

Публикация проекта:
1. Добавить запись в public.projects
2. Поставить published = true
3. Заполнить title, slug, short_description, type, status
4. При необходимости указать cover_url

Фронтенд всё ещё требует обычного веб-хостинга (например Vercel).
Supabase используется как база/API, а не как HTML-хостинг.
