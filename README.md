# EasyWordle

A fun and lightweight Minecraft plugin that brings the classic Wordle game into your server. Challenge your players with daily word puzzles in both English and Spanish, and enjoy a smooth and interactive GUI-based gameplay experience.

---

## 🎮 Features

- 🌍 **Bilingual Support**: Your choose your words in config.yml!
- - 🟩🟨⬛ **Classic Wordle Mechanics**: Green for correct position, yellow for correct letter in wrong place, gray for incorrect.
- 🎉 **Victory Recognition**: Celebrate your players' achievements.
- 🔌 **PlaceholderAPI Support**: Display stats or status with placeholders.
- 📦 **Modular Word Lists**: Easily add or edit words in `/words.yml`.

---

## 📦 Installation

1. Download the latest `.jar` file from the [Releases](https://github.com/crituhx/easywordle/releases) section.
2. Place the plugin into your server's `/plugins` folder.
3. Start or restart the server.
4. (Optional) Install PlaceholderAPI if you want to use placeholders.

---

## 📜 Commands

| Command | Description |
|--------|-------------|
| `/ewordle help` | See all the EasyWordleCommands! |
| `/ewordle duel` | Start a duel (check the subcommands) |
| `/ewordle play`    | Play Wordle in Minecraft! |
| `/ewordle list`    | See the all words! |
| `/ewordle reload`    | Reload configuration! 

 and more ...    

(More commands and permissions will be added in future updates).

---

## 📁 File Structure

```plaintext
/plugins/EasyWordle/
├── config.yml
├── words.yml
├── Stats/
│   ├── uuid.yml

(The stats folder is created when a player plays for the first time, not when the server is turned on).
