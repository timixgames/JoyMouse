# 🎮 JoyMouse v12.6 ENHANCED (BETA)

**Control your computer with a gamepad**

[![Python Version](https://img.shields.io/badge/python-3.6%2B-blue)](https://www.python.org/)
[![Status: Beta](https://img.shields.io/badge/status-beta-orange)](https://github.com/)

---

## English

### 🎯 Description
JoyMouse is a Python application that allows you to control your computer's mouse and keyboard using a gamepad. Perfect for:
- 💻 Using your computer from a distance (connected to TV)
- 🛋️ Comfortable couch browsing
- 🎮 When you're sick and want to control your PC while lying down
- 🖥️ Media center control

> ⚠️ **Beta Version**: This software is in active development. Some features may be rough around the edges. Feedback and bug reports are welcome!

### ✨ Features
- **🖱️ Mouse Control** - Left stick moves cursor with smooth acceleration
- **📜 Scroll Control** - Right stick provides 4-direction scrolling with inertia
- **⌨️ Keyboard Mode** - Automatically activates in Start menu and context menus
- **🔊 Media Keys** - D-Pad controls volume (left/right) and brightness (up/down)
- **🎯 Drag & Drop** - Hold A button to drag items
- **⚡ Hotkeys** - LT + D-Pad to adjust speed/DPI on the fly
- **⚙️ Configurable** - All settings saved to JSON file
- **🌐 Bilingual** - English and Russian interface

### 🎮 Controls

| Button | Function |
|--------|----------|
| Left Stick | Move cursor |
| Right Stick | Scroll (4 directions) |
| A | Left click / Hold for drag |
| B | Toggle keyboard mode |
| X | Middle click |
| Y / Home | Open Start menu |
| Back | Toggle scroll mode |
| Start | Exit program |
| LT | Backspace |
| RT | Delete |
| D-Pad ←/→ | Volume down/up |
| D-Pad ↑/↓ | Brightness up/down |
| LT + D-Pad ↑/↓ | Adjust cursor speed |
| LT + D-Pad ←/→ | Adjust DPI |

### 🔧 Installation

1. **Install Python 3.6+** if you don't have it
2. **Install required packages:**
   ```bash
   pip install inputs pynput psutil wmi pywin32
Download joymouse.py from this repository

Connect your gamepad (Xbox, PlayStation, or any compatible controller)

Run the program:

bash
python joymouse.py
⚙️ Configuration
On first run, joymouse_config.json is created automatically. You can edit:

base_speed - cursor speed at small stick movements (default: 0.35)

max_speed - maximum cursor speed (default: 2.0)

dpi - overall sensitivity multiplier (default: 1.2)

deadzone_x/y - stick deadzone values

acceleration - acceleration factor (1.0-5.0)

smoothing - smoothness of cursor movement (0.3-0.95)

scroll_sensitivity - scroll speed

And many more options!

🚀 Tips
Use LT + D-Pad up/down to adjust speed in real-time

Use LT + D-Pad left/right to adjust DPI

Program automatically switches to keyboard mode in Start menu

Press B to manually toggle keyboard/mouse mode

🐛 Known Issues (Beta)
Some gamepads may have different axis mappings (ABS_Z/ABS_RZ for triggers)

Brightness control may not work on all monitors (uses WMI/F11/F12/PowerShell fallbacks)

Steam/Game Bar might intercept the Home button

📦 Dependencies
inputs - gamepad input handling

pynput - mouse and keyboard control

psutil - process checking for Steam/Game Bar

wmi - Windows brightness control

pywin32 - Windows API access

👨‍💻 Author
Created by [Your Name]

⭐ Support
If you find this useful, please give a star on GitHub!

📝 Feedback
This is a beta version! Found a bug? Have a suggestion? Please open an issue on GitHub.

## Русский

JoyMouse - это Python-программа для управления компьютером с помощью геймпада. Идеально подходит для:

💻 Использования компьютера на расстоянии (подключение к телевизору)

🛋️ Комфортного сёрфинга с дивана

🎮 Когда болеешь и хочешь управлять ПК лёжа

🖥️ Управления медиацентром

⚠️ Бета-версия: Программа находится в активной разработке. Некоторые функции могут работать не идеально. Баг-репорты и обратная связь приветствуются!

✨ Возможности
🖱️ Управление мышью - левый стик двигает курсор с плавным ускорением

📜 Скролл - правый стик обеспечивает скролл в 4 направлениях с инерцией

⌨️ Режим клавиатуры - автоматически включается в меню Пуск и контекстных меню

🔊 Медиа-клавиши - D-Pad управляет громкостью (влево/вправо) и яркостью (вверх/вниз)

🎯 Перетаскивание - удерживайте A для перетаскивания объектов

⚡ Горячие клавиши - LT + D-Pad для быстрой настройки скорости/DPI

⚙️ Настройки - все параметры сохраняются в JSON файл

🌐 Двуязычность - интерфейс на английском и русском

🎮 Управление
Кнопка	Функция
Левый стик	Движение курсора
Правый стик	Скролл (4 направления)
A	Левый клик / Удержание для перетаскивания
B	Переключение режима клавиатуры
X	Средний клик
Y / Home	Открыть меню Пуск
Back	Переключение режима скролла
Start	Выход из программы
LT	Backspace
RT	Delete
D-Pad ←/→	Громкость -/+
D-Pad ↑/↓	Яркость +/-
LT + D-Pad ↑/↓	Настройка скорости курсора
LT + D-Pad ←/→	Настройка DPI
🔧 Установка
Установите Python 3.6+, если его нет

Установите необходимые пакеты:

bash
pip install inputs pynput psutil wmi pywin32
Скачайте joymouse.py из этого репозитория

Подключите геймпад (Xbox, PlayStation или любой совместимый)

Запустите программу:

bash
python joymouse.py
⚙️ Настройка
При первом запуске автоматически создаётся joymouse_config.json. Вы можете редактировать:

base_speed - скорость при малых отклонениях стика (по умолчанию: 0.35)

max_speed - максимальная скорость курсора (по умолчанию: 2.0)

dpi - общий множитель чувствительности (по умолчанию: 1.2)

deadzone_x/y - мёртвая зона стиков

acceleration - фактор ускорения (1.0-5.0)

smoothing - плавность движения (0.3-0.95)

scroll_sensitivity - скорость скролла

И многие другие параметры!

🚀 Советы
Используйте LT + D-Pad вверх/вниз для настройки скорости на лету

Используйте LT + D-Pad влево/вправо для настройки DPI

Программа автоматически переключается в режим клавиатуры в меню Пуск

Нажмите B для ручного переключения режима мышь/клавиатура

🐛 Известные проблемы (Бета)
У некоторых геймпадов могут отличаться оси (ABS_Z/ABS_RZ для триггеров)

Управление яркостью может работать не на всех мониторах (используются WMI/F11/F12/PowerShell)

Steam/Game Bar может перехватывать кнопку Home

📦 Зависимости
inputs - обработка ввода с геймпада

pynput - управление мышью и клавиатурой

psutil - проверка процессов Steam/Game Bar

wmi - управление яркостью в Windows

pywin32 - доступ к Windows API


👨‍💻 Автор
Создано [Твоё Имя]

⭐ Поддержка
Если программа полезна, поставьте звёздочку на GitHub!

📝 Обратная связь
Это бета-версия! Нашли баг? Есть предложение? Создайте issue на GitHub.
