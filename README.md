# 🧩 Rubik's Simulator

🧩

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen?style=for-the-badge)](https://volkovhl.github.io/Rubik-s-Simulator/)
[![GitHub stars](https://img.shields.io/github/stars/volkovhl/Rubik-s-Simulator?style=for-the-badge)](https://github.com/volkovhl/Rubik-s-Simulator/stargazers)
[![GitHub license](https://img.shields.io/github/license/volkovhl/Rubik-s-Simulator?style=for-the-badge)](https://github.com/volkovhl/Rubik-s-Simulator/blob/main/LICENSE)

Интерактивный 3D симулятор кубика Рубика с правильным маппингом алгоритмов. Оптимизирован для смартфонов и тренировок спидкуберов.

---

## ✨ Особенности

- 🎯 **Правильный маппинг** — алгоритмы работают относительно выбранной передней и верхней стороны
- 🔄 **Смена ориентации** — выбор любой стороны как передней (F/R/B/L) и верхней (U/D)
- 📱 **Мобильная версия** — компактный интерфейс, удобный для смартфонов
- 🎮 **Крестик управления** — поворот всего кубика в 4 направлениях
- ⚡ **Пиф-пафы** — встроенные алгоритмы для тренировок
- 🎨 **3D графика** — плавные вращения с кватернионной интерполяцией
- 🏆 **Для спидкуберов** — тренируйте алгоритмы в любой ориентации

---

## 🎮 Управление

### Мобильные устройства

| Элемент | Действие |
|---------|----------|
| 🟣 **Крестик внизу слева** | Поворот всего кубика |
| 🎯 **Цветные кружки сверху** | Выбор передней/верхней стороны |
| 👆 **Касание граней** | Поворот слоя кубика |

### Клавиатура (ПК)

| Клавиша | Действие |
|---------|----------|
| 🖱️ **Клик по грани** | Поворот слоя |
| 🖱️ **Drag & Drop** | Вращение всего кубика |

---

## 🧠 Встроенные алгоритмы

| Кнопка | Алгоритм | Название |
|--------|----------|----------|
| ⬜ **R U R' U'** | `R U R' U'` | Верхний пиф-паф |
| ⬜ **R' D R D'** | `R' D R D'` | Нижний пиф-паф |
| 🟠 **U R U' R' U' F' U F** | `U R U' R' U' F' U F` | Вставка ребра |
| 🟢 **F R U R' U' F'** | `F R U R' U' F'` | Крест OLL |
| 🟡 **R U R' U R U2 R'** | `R U R' U R U2 R'` | Sune OLL |
| 🔴 **U R U' L' U R' U' L** | `U R U' L' U R' U' L` | Перестановка углов |
| 🟢 **ЦЕНТР** | — | Центрировать / Перевернуть |

---

## ⚙️ Технические детали

- Чистый HTML/CSS/JavaScript (без зависимостей)
- 3D через CSS transforms
- Кватернионная интерполяция для плавных поворотов
- Адаптивный дизайн для мобильных устройств
- Полный маппинг всех 24 ориентаций кубика
- Размер кубика: 3×3×3

---

## 📱 Скриншоты

| Мобильная версия | Выбор ориентации | Алгоритмы |
|------------------|------------------|-----------|
| ![mobile](https://via.placeholder.com/200x400/1a1a1a/ffaa00?text=Rubik's+Simulator) | ![orientation](https://via.placeholder.com/200x400/4caf50/ffffff?text=F+U) | ![algo](https://via.placeholder.com/200x400/ff8800/ffffff?text=R+U+R'+U') |

---

## 🚀 Установка и запуск

1. Склонируйте репозиторий:
```bash
git clone https://github.com/volkovhl/Rubik-s-Simulator.git

📄 Лицензия
MIT License © 2026 volkovhl

⭐ Поддержка
Если проект вам понравился — поставьте звездочку на GitHub! Это поможет другим найти этот симулятор.

https://img.shields.io/github/stars/volkovhl/Rubik-s-Simulator?style=social

🔗 Ссылки
Демо

GitHub

YouTube (скоро)
