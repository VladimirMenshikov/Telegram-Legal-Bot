# 📸 Скриншоты работы Telegram-бота «Юридический ассистент по недвижимости»

Ниже представлены основные этапы взаимодействия пользователя с Telegram-ботом и обработка его заявки на консультацию.

---

## 🗨️ Диалог с пользователем

### 🔹 Шаг 1: Первый вопрос от пользователя

![Диалог 1](./dialog_step_1.jpg)

---

### 🔹 Шаг 2: Уточнение от бота

![Диалог 2](./dialog_step_2.jpg)

---

### 🔹 Шаг 3: Финальный ответ с записью на консультацию

![Диалог 3](./dialog_step_3.jpg)

---

## 📜 Журнал общения (лог чата)

Бот сохраняет 10 последних сообщений в контексте и использует их для построения ответа.

![Лог чата](./chat_log.jpg)

---

## 📋 Заявка на консультацию (таблица Airtable)

Контактные данные и история общения пользователя автоматически сохраняются в Airtable:

- Имя
- Телефон
- Вопрос
- Резюме диалога

![Таблица Airtable](./dialog_step_1-1.jpg))

---

## ✉️ Уведомление администратору Telegram

После получения контактных данных бот автоматически отправляет уведомление администратору.

![Сообщение админа](./message_to_admin.jpg)
