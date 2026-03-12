# 🧩 Rubik's Simulator
**Rubik's Simulator — интерактивный 3D кубик Рубика с алгоритмами сборки. Вращайте грани, меняйте ориентацию, изучайте пиф-пафы прямо в браузере. Оптимизирован для мобильных устройств и ПК.**

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen?style=for-the-badge)](https://volkovhl.github.io/Rubik-s-Simulator/)
[![GitHub stars](https://img.shields.io/github/stars/volkovhl/Rubik-s-Simulator?style=for-the-badge)](https://github.com/volkovhl/Rubik-s-Simulator/stargazers)
[![GitHub license](https://img.shields.io/github/license/volkovhl/Rubik-s-Simulator?style=for-the-badge)](https://github.com/volkovhl/Rubik-s-Simulator/blob/main/LICENSE)

---

## ✨ Возможности
- 🎮 **Управление**: мышкой (drag) или кнопками на экране
- 🔄 **Смена ориентации**: кнопки поворота всего куба
- 🧩 **Алгоритмы**: готовые последовательности (R U R' U', F R U R' U' F' и др.)
- 📱 **Адаптивный дизайн**: удобно на телефоне и ПК
- 🎯 **CFOP**: поддержка основных этапов метода

## 🛠 Технологии
- Чистый HTML, CSS и JavaScript (без библиотек)
- 3D трансформации CSS
- Drag-повороты для интерактивности

## 📲 Как использовать
1. Откройте [демо](https://volkovhl.github.io/Rubik-s-Simulator/)
2. Вращайте грани перетаскиванием
3. Используйте кнопки внизу для алгоритмов
4. Меняйте ориентацию куба стрелками

## 🧠 Встроенные алгоритмы

### Пиф-пафы
- `R U R' U'` — правый
- `U R U' R'` — верхний  
- `R' D R D'` — нижний
- `R' D2 R U` — специальный

### F2L (First Two Layers)
- `U R U' R' U' F' U F` — вставка ребра
- `U R U' R' F R' F' R` — правая вставка пары
- `U' L' U L F' L F L'` — левая вставка пары

### OLL (Orientation of Last Layer)
- `F R U R' U' F'` — крест OLL
- `R U R' U R U2 R'` — Sune OLL

### PLL (Permutation of Last Layer)
- `U R U' L' U R' U' L` — перестановка углов

### Служебные
- 🔀 **ПЕРЕМЕШАТЬ** — 15 случайных ходов
- 🎯 **ЦЕНТР** — центрировать куб
- 🔄 **СБРОС** — перезагрузить страницу

> 💡 **Подсказка**: Можно выполнять алгоритмы в любой ориентации — симулятор сам преобразует ходы относительно текущего положения куба (выбранных граней F и U)!

## ⚙️ Технические детали

- Чистый HTML/CSS/JavaScript (без зависимостей)
- 3D через CSS transforms
- Кватернионная интерполяция для плавных поворотов
- Адаптивный дизайн для мобильных устройств
- Полный маппинг всех 24 ориентаций кубика
- Размер кубика: 3×3×3

