# 🤖 Carlos21_bot — Asistente de Programación en Telegram

Bot de Telegram impulsado por **Google Gemini AI** que actúa como asistente experto en programación. Responde preguntas de código, depura errores y optimiza scripts con memoria de conversación activa.

---

## ✨ Características

- 🧠 **Memoria de conversación** — recuerda el contexto de toda la sesión
- 💻 **Especializado en programación** — actúa como ingeniero de software senior
- ⚡ **Sin dependencias pesadas** — usa `requests` directamente, compatible con Termux/Android
- 🔄 **Comando /reset** — borra el historial y empieza de cero

---

## 🛠️ Tecnologías

- Python 3
- [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)
- [Google Gemini API](https://aistudio.google.com/) (via HTTP directo)

---

## 🚀 Instalación

### 1. Clona el repositorio
```bash
git clone https://github.com/TU_USUARIO/carlos21_bot.git
cd carlos21_bot
```

### 2. Instala las dependencias
```bash
pip install python-telegram-bot requests
```

### 3. Configura tus credenciales
Crea un archivo `.env` en la raíz del proyecto:
```
TELEGRAM_TOKEN=tu_token_de_botfather
GEMINI_API_KEY=tu_api_key_de_google
```

> 🔑 Obtén tu token en [@BotFather](https://t.me/BotFather)  
> 🔑 Obtén tu API key en [Google AI Studio](https://aistudio.google.com/apikey)

### 4. Corre el bot
```bash
python bot_sin_genai.py
```

---

## 📱 Compatible con Termux (Android)

Este bot fue desarrollado y probado directamente desde **Termux en Android**, sin necesidad de un servidor.

```bash
# En Termux
pip install python-telegram-bot
python bot_sin_genai.py
```

---

## 💬 Comandos disponibles

| Comando | Descripción |
|--------|-------------|
| `/start` | Inicia o reinicia el bot |
| `/reset` | Borra el historial de conversación |

---

## 📄 Licencia

MIT License — libre para usar y modificar.
