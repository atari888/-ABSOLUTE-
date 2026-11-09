<div align="center">

**English** 

# ✨ ABSOLUTE

**A cosmetic PvP mod for Minecraft 1.21.4**

Visuals only. No cheats.

> [!IMPORTANT]
> **Fabric API is required!** The mod will not start without it.
> Download [Fabric API](https://modrinth.com/mod/fabric-api) for **1.21.4** and put it in the `mods` folder next to Absolute.

![Minecraft](https://img.shields.io/badge/Minecraft-1.21.4-62B47A?style=for-the-badge)
![Fabric](https://img.shields.io/badge/Loader-Fabric-DBD0B4?style=for-the-badge)
![Side](https://img.shields.io/badge/Side-Client-5865F2?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-F7DF1E?style=for-the-badge)

**[📥 Download](../../releases/latest)** · **[🐞 Report a bug](../../issues)**

![Absolute](screenshots/main.png)

</div>

---

## 🛡️ Fair play

Absolute changes only how the game **looks**, not how it plays.

- **Client-side only**, so it works on any server
- **No** reach, killaura, autoclicker, ESP or other cheats
- Hitbox sizes and attack cooldown are **not changed**
- The mod gives no gameplay advantage

---

## 🧩 Modules

### 🎯 ViewModel · *Render*
Customize how the held item looks.
- **X / Y / Z** offset, scale and rotation, **separately for the right and left hand**
- Swing animation speed. Only the animation changes; attack speed stays the same

### 📦 Hitboxes · *Render*
Styles the hitboxes you turn on with `F3 + B`.
- Choose who to show them on: players, yourself (F5), hostile mobs, passive mobs and animals, items and XP, other
- A separate color for each type, line width, translucent fill
- Eye line and look vector

### 🧪 Potion HUD · *HUD*
A clean list of active effects.
- Icon, name with level, and timer
- An effect blinks when less than 5 seconds remain
- **HUD editor**: drag the panel with the mouse and change its scale with the scroll wheel. The panel snaps to the screen edges and center
- The vanilla effect icons in the top-right corner can be hidden

### 🌌 Custom Sky · *World*
Your own sky in the Overworld.
- **Skybox**: a seamless high-quality night sky (6 faces at 2048 px)
- **Gradient**: two colors with twinkling stars
- **Custom image**: put `sky.png` or `sky.jpg` in the `config/pvpvisuals/` folder
  - The **"Open"** button opens that folder, and **"Reload"** rereads the file without restarting the game
  - A 2:1 (equirectangular) panorama works best
  - Scale, offset, rotation and brightness are adjustable
- Rotation speed, vanilla sun, moon and stars, sky-colored fog, smooth horizon

> 💡 If a shader pack is enabled in Iris, the shader draws the sky and Custom Sky turns itself off.

### 🔧 Misc · *Misc*
- **Low fire** with adjustable height
- **No camera shake** when taking damage
- **Custom tripwire color**. You can recolor only tripwire strung between hooks
- **Custom crosshair**: color with transparency, length, thickness, gap, dot, outline
  - A draggable preview window next to the menu
  - 1x / 2x / 3x / 5x zoom and different backgrounds

---

## 📸 Screenshots

| Menu | ViewModel |
|:---:|:---:|
| ![Menu](screenshots/menu.png) | ![ViewModel](screenshots/viewmodel.png) |
| **Hitboxes** | **Custom Sky** |
| ![Hitboxes](screenshots/hitboxes.png) | ![Custom Sky](screenshots/sky.png) |
| **Potion HUD** | **Crosshair** |
| ![Potion HUD](screenshots/potionhud.png) | ![Crosshair](screenshots/crosshair.png) |

---

## 📥 Installation

1. Install **Minecraft 1.21.4** and **[Fabric Loader](https://fabricmc.net/use/) 0.16 or newer**. Select the **Fabric 1.21.4** profile in your launcher
2. Download **[Fabric API](https://modrinth.com/mod/fabric-api)** for 1.21.4
3. Download **`Absolute-1.0.0.jar`** from [Releases](../../releases/latest)
4. Put both files in your `mods` folder:
   - **Windows:** `%APPDATA%\.minecraft\mods`
   - **macOS:** `~/Library/Application Support/minecraft/mods`
   - **Linux:** `~/.minecraft/mods`
5. Launch the game

### ✅ Compatibility
| Mod | Status |
|---|---|
| Sodium | ✅ Works |
| Iris | ✅ Works (with a shader pack enabled, the shader draws the sky) |

---

## ⌨️ Controls

| Input | Action |
|---|---|
| `Right Shift` | Open or close the menu (rebind in *Options → Controls → Absolute*) |
| `LMB` on a module | Turn the module on or off |
| `RMB` on a module or `›` | Open module settings |
| `Esc` | Leave module settings or close the menu |
| Typing in the menu | Search modules |
| Drag the avatar | Move the menu (`RMB` on the avatar centers it again) |
| `F3 + B` | Show hitboxes (styled by the Hitboxes module) |

🌐 Switch the menu language in the bottom-left corner: **RU / EN / 中文**

---

## ⚙️ Settings

- All settings are stored in `config/absolutepvp.json`
- Changes apply instantly and are **saved automatically**
- To reset everything, delete this file
- A config from an older version (`config/pvpvisuals.json`) is renamed automatically

---

## 🐞 Found a bug?

Open an [Issue](../../issues) and include:
- the mod and Fabric Loader versions;
- a list of your other mods;
- the log from `.minecraft/logs/latest.log`.

---

## 📜 Licenses

- The mod's code is licensed under **[MIT](LICENSE)**
- The **Nunito**, **Orbitron** and **Resource Han Rounded** fonts are licensed under the **SIL Open Font License 1.1**

<div align="center">

⭐ **If you like the mod, star the repository!**

</div>

<div align="center">

[English](README.md) | **Русский**

# ✨ ABSOLUTE

**Косметический ПвП-мод для Minecraft 1.21.4**

Только визуал. Никаких читов.

> [!IMPORTANT]
> **Обязательно нужен Fabric API!** Без него мод не запустится.
> Скачай [Fabric API](https://modrinth.com/mod/fabric-api) для версии **1.21.4** и положи его в папку `mods` рядом с Absolute.

![Minecraft](https://img.shields.io/badge/Minecraft-1.21.4-62B47A?style=for-the-badge)
![Fabric](https://img.shields.io/badge/Loader-Fabric-DBD0B4?style=for-the-badge)
![Side](https://img.shields.io/badge/Side-Client-5865F2?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-F7DF1E?style=for-the-badge)

**[📥 Скачать](../../releases/latest)** · **[🐞 Сообщить о баге](../../issues)**

![Absolute](screenshots/main.png)

</div>

---

## 🛡️ Честный мод

Absolute меняет только то, **как выглядит** игра, а не то, как в неё играют.

- Работает **только на клиенте**, поэтому подходит для любого сервера
- **Нет** reach, killaura, автокликера, ESP и других читов
- Размеры хитбоксов и перезарядка атаки **не меняются**
- Мод не даёт игрового преимущества

---

## 🧩 Модули

### 🎯 ViewModel · *Рендер*
Настрой, как выглядит предмет в руке.
- Смещение по **X / Y / Z**, масштаб и поворот, **отдельно для правой и левой руки**
- Скорость анимации удара. Меняется только анимация, скорость атаки остаётся прежней

### 📦 Hitboxes · *Рендер*
Стилизация хитбоксов, которые включаются через `F3 + B`.
- Выбор, на ком их показывать: игроки, ты сам (F5), враждебные мобы, мирные мобы и животные, предметы и опыт, прочее
- Свой цвет для каждого типа, толщина линий, полупрозрачная заливка
- Линия глаз и вектор взгляда

### 🧪 Potion HUD · *HUD*
Удобный список активных эффектов.
- Иконка, название с уровнем и таймер
- Эффект мигает, когда до его окончания остаётся меньше 5 секунд
- **Редактор HUD**: двигай панель мышью, меняй масштаб колесом. Панель примагничивается к краям и центру экрана
- Ванильные иконки эффектов в правом верхнем углу можно скрыть

### 🌌 Custom Sky · *Мир*
Своё небо в верхнем мире.
- **Скайбокс**: бесшовное ночное небо в высоком качестве (6 граней по 2048 px)
- **Градиент**: два цвета и мерцающие звёзды
- **Своя картинка**: положи `sky.png` или `sky.jpg` в папку `config/pvpvisuals/`
  - Кнопка **«Открыть»** открывает эту папку, **«Обновить»** перечитывает файл без перезапуска игры
  - Лучше всего подходит панорама 2:1 (equirectangular)
  - Настраиваются масштаб, сдвиг, поворот и яркость
- Скорость вращения, ванильные солнце, луна и звёзды, туман в цвет неба, плавный горизонт

> 💡 Если в Iris включён шейдерпак, небо рисует шейдер, и Custom Sky отключается сам.

### 🔧 Misc · *Разное*
- **Низкий огонь** с настраиваемой высотой
- **Без тряски камеры** при получении урона
- **Свой цвет нитки** (tripwire). Можно перекрасить только нитку, натянутую между крючками
- **Свой прицел**: цвет с прозрачностью, длина, толщина, зазор, точка, обводка
  - Окно предпросмотра рядом с меню, его можно перетаскивать
  - Приближение 1x / 2x / 3x / 5x и разные фоны

---

## 📸 Скриншоты

| Меню | ViewModel |
|:---:|:---:|
| ![Меню](screenshots/menu.png) | ![ViewModel](screenshots/viewmodel.png) |
| **Hitboxes** | **Custom Sky** |
| ![Hitboxes](screenshots/hitboxes.png) | ![Custom Sky](screenshots/sky.png) |
| **Potion HUD** | **Прицел** |
| ![Potion HUD](screenshots/potionhud.png) | ![Прицел](screenshots/crosshair.png) |

---

## 📥 Установка

1. Установи **Minecraft 1.21.4** и **[Fabric Loader](https://fabricmc.net/use/) 0.16 или новее**. В лаунчере выбери профиль **Fabric 1.21.4**
2. Скачай **[Fabric API](https://modrinth.com/mod/fabric-api)** для версии 1.21.4
3. Скачай **`Absolute-1.0.0.jar`** из раздела [Releases](../../releases/latest)
4. Положи оба файла в папку `mods`:
   - **Windows:** `%APPDATA%\.minecraft\mods`
   - **macOS:** `~/Library/Application Support/minecraft/mods`
   - **Linux:** `~/.minecraft/mods`
5. Запусти игру

### ✅ Совместимость
| Мод | Статус |
|---|---|
| Sodium | ✅ Работает |
| Iris | ✅ Работает (при включённом шейдерпаке небо рисует шейдер) |

---

## ⌨️ Управление

| Действие | Что делает |
|---|---|
| `Right Shift` | Открыть или закрыть меню (клавишу можно сменить: *Настройки → Управление → Absolute*) |
| `ЛКМ` по модулю | Включить или выключить модуль |
| `ПКМ` по модулю или `›` | Открыть настройки модуля |
| `Esc` | Выйти из настроек модуля или закрыть меню |
| Ввод текста в меню | Поиск модулей |
| Перетаскивание аватарки | Переместить меню (`ПКМ` по аватарке возвращает его в центр) |
| `F3 + B` | Показать хитбоксы (их стиль задаёт модуль Hitboxes) |

🌐 Язык меню переключается в левом нижнем углу: **RU / EN / 中文**

---

## ⚙️ Настройки

- Все настройки хранятся в файле `config/absolutepvp.json`
- Изменения применяются сразу и **сохраняются автоматически**
- Чтобы сбросить всё, удали этот файл
- Если остался файл от старой версии (`config/pvpvisuals.json`), он переименуется автоматически

---

## 🐞 Нашёл баг?

Создай [Issue](../../issues) и укажи:
- версию мода и Fabric Loader;
- список остальных модов;
- лог из файла `.minecraft/logs/latest.log`.

---

## 📜 Лицензии

- Код мода распространяется под лицензией **[MIT](LICENSE)**
- Шрифты **Nunito**, **Orbitron** и **Resource Han Rounded** распространяются под лицензией **SIL Open Font License 1.1**

<div align="center">

⭐ **Если мод понравился, поставь звезду репозиторию!**

</div>
