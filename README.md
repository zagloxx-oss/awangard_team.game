# awangard_team.game

# AWANGARD-engine

**AWANGARD-engine** is a browser-based 3D world editor and game creator. It allows you to build landscapes, place objects, add lighting, and export playable HTML games without writing a single line of code. Everything runs locally in your browser – no server or internet connection required (except for loading the Three.js and Cannon.js libraries from CDN on first launch).

---

## Features

- **Terrain editing** – raise, lower, or smooth the ground with an adjustable brush (radius and strength).
- **Texture painting** – paint custom images onto the terrain using a brush tool with circle or square shape.
- **Objects library** – place cubes, spheres, cylinders, trees (birch, pine, oak), bushes (3 types), rocks (3 sizes), glass panes, furniture (table, chair, lamp), street lamps, bulbs, doors, sound markers, and point lights.
- **Walls** – build rectangular and triangular walls with adjustable width, height, and angle (for triangles).
- **Lighting** – add point lights with configurable intensity and distance; also includes a dynamic day/night cycle that affects the sky color, sun position, and ambient light.
- **Sound sources** – place audio markers with adjustable volume and range (playback in exported games is coming soon).
- **Transform tools** – move, rotate, and scale any object using the transform controls.
- **Grouping** – combine multiple objects into a group for easier manipulation; ungroup at any time.
- **Collision** – toggle physical collision on/off for any object.
- **Save/Load** – export your entire project as a JSON file (including terrain heights, textures, brush data, and all objects) and load it back later.
- **Export to HTML** – generate a standalone, playable HTML game from your scene. The exported game includes:
  - First-person movement (WASD) and jumping (Space).
  - Interactive doors (press F to open/close).
  - Day/night cycle that runs in real time.
  - Collision with terrain and objects (using Cannon.js physics).
- **User textures** – upload your own images as wall textures, object sprites, or brush stamps.
- **No backend required** – everything is client-side; the editor works offline after the initial load.

---

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, or Opera).
- An internet connection for the first load (to fetch Three.js and Cannon.js from CDN). After that, you can work offline if your browser caches the libraries.

- # AWANGARD-engine (Русская версия)

**AWANGARD-engine** — это браузерный 3D-редактор миров и конструктор игр. Он позволяет создавать ландшафты, расставлять объекты, настраивать освещение и экспортировать играбельные HTML-игры без написания кода. Всё работает локально в вашем браузере — сервер или интернет не требуются (кроме первой загрузки библиотек Three.js и Cannon.js с CDN).

---

## Возможности

- **Редактирование рельефа** – поднимайте, опускайте или сглаживайте землю кистью с настраиваемыми радиусом и силой.
- **Рисование текстур** – наносите свои изображения на ландшафт с помощью кисти (круглой или квадратной формы).
- **Библиотека объектов** – размещайте кубы, сферы, цилиндры, деревья (берёза, сосна, дуб), кусты (3 вида), камни (3 размера), стеклянные панели, мебель (стол, стул, торшер), фонарные столбы, лампочки, двери, звуковые маркеры и точечные источники света.
- **Стены** – стройте прямоугольные и треугольные стены с регулируемой шириной, высотой и углом (для треугольных).
- **Освещение** – добавляйте точечные источники света с настраиваемой интенсивностью и дальностью; также доступен динамический цикл дня и ночи, меняющий цвет неба, положение солнца и интенсивность окружающего света.
- **Звуковые источники** – размещайте маркеры звука с регулировкой громкости и дальности (воспроизведение в экспортированных играх пока в разработке).
- **Инструменты трансформации** – перемещайте, вращайте и масштабируйте любые объекты с помощью контроллера трансформации.
- **Группировка** – объединяйте несколько объектов в группу для удобного редактирования; разгруппировывайте в любой момент.
- **Коллизия** – включайте/отключайте физическое столкновение для любого объекта.
- **Сохранение/загрузка** – экспортируйте весь проект в JSON-файл (включая высоты рельефа, текстуры, данные кисти и все объекты) и загружайте обратно позже.
- **Экспорт в HTML** – генерируйте самостоятельную играбельную HTML-игру из вашей сцены. Экспортированная игра включает:
  - Управление от первого лица (WASD) и прыжок (пробел).
  - Интерактивные двери (нажмите F для открытия/закрытия).
  - Цикл дня и ночи в реальном времени.
  - Физику столкновений с рельефом и объектами (на Cannon.js).
- **Пользовательские текстуры** – загружайте свои изображения как текстуры стен, спрайты объектов или штампы для кисти.
- **Без бэкенда** – всё работает на стороне клиента; после первой загрузки редактор может работать офлайн.

---

## Начало работы

### Требования

- Современный веб-браузер (Chrome, Firefox, Edge или Opera).
- Интернет-соединение для первой загрузки (чтобы получить Three.js и Cannon.js с CDN). После загрузки библиотек можно работать офлайн, если браузер закэширует их.
