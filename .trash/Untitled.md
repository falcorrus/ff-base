---
title: >-
  Build & Launch A Multi Tenant Complex App With Claude Code, Supabase and MCP
  (Step by Step Tutorial) - YouTube
description: >-
  ► Clone This App (+All My Other Apps), Exclusive Tutorials & Support:
  https://www.patreon.com/jamesnocode► Comprehensive FlutterFlow Training &
  Private Commu...
author: YouTube
source: https://www.youtube.com/watch?v=PUrz6ZC5Q0g
created: "2025-09-01"
tags:
  - hover-notes
  - youtube
---

### Введение
- Обсуждение использования Claude Code для ускорения разработки.
- Эксперименты с Claude Code на стороннем проекте.
### Планируемое приложение
- Будет создано реальное приложение с нуля.
- Многопользовательское приложение (multi-tenant app):
- Несколько клиентов могут управлять своими ресурсами (например, своими клиентами).
- Внутренняя доска идей (internal idea board):
- Место, где команды могут отправлять отзывы, загружать лучшие идеи и отслеживать их прогресс.
- Прогресс идей от предложения до реализации.
### План разработки приложения
- Начнем с проектирования архитектуры и схемы базы данных.
- Затем разработаем функции.
- Протестируем все шаг за шагом.
- В конце развернем приложение, чтобы можно было попробовать его вживую.
- К концу этого видео будет показано, как использовать Claude Code в повседневной работе, а также как его можно взять и построить что-то практичное, готовое к запуску.
### Используемые технологии
- Supabase
- SvelteKit
- Claude Code
### Основы
- Создание проекта Supabase.
- Определение схемы (+ минимальные данные для заполнения).
- Включение RLS (Row Level Security) с изоляцией арендаторов (`org_id`) + ролями.
- Настройка аутентификации (email magic link, опционально Google).