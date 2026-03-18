<p align="center">
  <a href="https://volkovhl.github.io/Rubik-s-Simulator/">
    <img src="https://github.com/volkovhl/Rubik-s-Simulator/raw/main/Rubik's.webp" alt="Rubik's Simulator Preview" width="640" style="border-radius:12px; box-shadow: 0 8px 32px rgba(0,0,0,0.5);">
  </a>
</p>

<h1 align="center">
  🧩 Rubik's Simulator
</h1>

<p align="center">
  <strong>Интерактивный 3D-симулятор кубика Рубика в браузере</strong><br>
  Вращайте грани, изучайте алгоритмы, тренируйте CFOP — всё на чистом HTML/CSS/JS
</p>

<p align="center">
  <a href="https://volkovhl.github.io/Rubik-s-Simulator/">
    <img src="https://img.shields.io/badge/ЗАПУСТИТЬ_ДЕМО-00D4FF?style=for-the-badge&logo=google-chrome&logoColor=white&labelColor=111" alt="Live Demo">
  </a>
  &nbsp;
  <a href="https://github.com/volkovhl/Rubik-s-Simulator/stargazers">
    <img src="https://img.shields.io/github/stars/volkovhl/Rubik-s-Simulator?style=for-the-badge&logo=github&logoColor=white&labelColor=111" alt="Stars">
  </a>
  &nbsp;
  <a href="https://github.com/volkovhl/Rubik-s-Simulator/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/volkovhl/Rubik-s-Simulator?style=for-the-badge&logo=opensourceinitiative&logoColor=white&labelColor=111" alt="License">
  </a>
</p>

<p align="center">
  <img src="https://github.com/volkovhl/Rubik-s-Simulator/raw/main/Rubik's%20fish.webp" alt="Rubik's Fish Pattern Example" width="320" style="border-radius:16px; box-shadow: 0 8px 32px rgba(0,0,0,0.5);">
</p>

---

## ✨ Возможности

<div align="center">
  <table>
    <tr>
      <td align="center" width="120">🖱️<br><b>Drag & Drop</b></td>
      <td align="center" width="120">🔄<br><b>Поворот куба</b></td>
      <td align="center" width="120">📋<br><b>Алгоритмы</b></td>
      <td align="center" width="120">📱<br><b>Мобильный</b></td>
    </tr>
  </table>
</div>

- 🎮 Управление мышкой (drag) или кнопками на экране  
- 🔄 Смена ориентации куба (кнопки поворота всего куба)  
- 🧩 Готовые алгоритмы и последовательности (пиф-пафы, F2L, OLL, PLL)  
- 📱 Полностью адаптивный дизайн — удобно на телефоне и ПК  
- 🎯 Поддержка метода CFOP (Cross → F2L → OLL → PLL)  
- 💡 Автоматическое преобразование алгоритмов под текущую ориентацию (F/U грани)

---

## 🛠 Технологии

- **Чистый стек**: HTML + CSS + JavaScript (без внешних библиотек)  
- **3D-рендеринг**: CSS 3D transforms + perspective  
- **Интерактивность**: Drag-жесты + touch events  
- **Плавность**: Кватернионная интерполяция поворотов  
- **Адаптивность**: Responsive layout + mobile-safe areas

---

## 📲 Как использовать

1. Откройте **[демо](https://volkovhl.github.io/Rubik-s-Simulator/)**  
2. Перетаскивайте грани для поворотов  
3. Используйте кнопки внизу для готовых алгоритмов  
4. Меняйте ориентацию куба стрелками или кнопками  
5. Нажмите **ПЕРЕМЕШАТЬ**, чтобы начать новую сборку

---

## 🧠 Встроенные алгоритмы

### Пиф-пафы
- `R U R' U'` — правый  
- `U R U' R'` — верхний  
- `R' D R D'` — нижний  
- `R' D2 R U` — специальный  

### F2L (вставки пар)
- `U R U' R' U' F' U F`  
- `U R U' R' F R' F' R` (правая пара)  
- `U' L' U L F' L F L'` (левая пара)  

### OLL
- `F R U R' U' F'` — крест  
- `R U R' U R U2 R'` — Sune  

### PLL
- `U R U' L' U R' U' L` — перестановка углов  

### Служебные
- 🔀 **ПЕРЕМЕШАТЬ** — 15 случайных ходов  
- 🎯 **ЦЕНТР** — центрировать куб  
- 🔄 **СБРОС** — перезагрузить

> 💡 **Важно**: Алгоритмы выполняются относительно текущих граней F и U — симулятор сам адаптирует ходы!

---

<p align="center">
  <a href="https://volkovhl.github.io/Rubik-s-Simulator/">▶️ Запустить симулятор</a>
  &nbsp;•&nbsp;
  <a href="https://github.com/volkovhl/Rubik-s-Simulator">📂 Исходный код</a>
</p>

<p align="center">
  <sub>MIT License • Сделано с ❤️ в Russia</sub>
</p>
