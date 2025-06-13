# 🛠️ Arcadia Tools

Arcadia Tools is the companion module for developer-facing utilities and editors within the Arcadia Engine ecosystem.

---

## 📦 Planned Features

- Map editor for ASCII tile-based maps
- Entity editor for prefab templates
- Visual component builder
- Runtime debug console
- Save/load integration tooling

---

## 🧩 Integration

All tools will export to interoperable formats consumed by `arcadia-core` and `arcadia-app`.

> Example workflow:
> - Design a map with Arcadia MapTool
> - Export `.amap.json`
> - Load via `MapLoader` in `arcadia-core`

---

## 📂 Modules

| Tool | Description |
|------|-------------|
| MapTool | ASCII/Tile map editor |
| PrefabBuilder | Define and tag entity presets |
| DebugConsole | Runtime visual state explorer (planned) |

---

## 🛤️ Roadmap

- [ ] MapTool MVP
- [ ] ComponentBuilder schema
- [ ] Save/load manager
