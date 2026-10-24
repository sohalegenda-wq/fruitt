# FRUIT MAYHEM 3D

Первая играбельная 3D-песочница на Godot 4.6.3: 10 фруктов, 3 карты, 8 устройств, ragdoll, X-Ray, машинка, строительство, сохранения и испытание.

## Скачать и запустить на Windows

1. Откройте [Releases](https://github.com/sohalegenda-wq/fruitt/releases/latest).
2. В разделе **Assets** скачайте **FRUIT_MAYHEM_Windows.zip**.
3. Нажмите по скачанному архиву правой кнопкой → **Извлечь всё**.
4. В извлечённой папке запустите **FRUIT_MAYHEM.exe**.
5. Нажмите **PLAY →**. Godot для запуска EXE не нужен.

[Прямая ссылка на Windows ZIP](https://github.com/sohalegenda-wq/fruitt/releases/latest/download/FRUIT_MAYHEM_Windows.zip)

Если релиз ещё не появился, посмотрите [сборку в Actions](https://github.com/sohalegenda-wq/fruitt/actions): архив публикуется после успешных проверок.

## Управление

WASD — ходить, мышь — осматриваться, Shift — бег, Space — прыжок.
ЛКМ — применить устройство, ПКМ — альтернативное действие.
Q — создать фрукты/предметы, Tab или 1–8 — выбрать устройство.
F — поднять/отпустить предмет, G — отпустить, Z — повернуть удерживаемое.
T — замедление времени, X — X-Ray, E — взаимодействие / машинка.
V — вид от третьего лица, P — свободная камера, F12 — фото.
Esc — пауза, настройки и сохранения.

На слабом ПК: Settings → Low / Very Low и 3D render scale примерно 0.65.

## Исходный проект

[Скачать проект Godot](https://github.com/sohalegenda-wq/fruitt/raw/refs/heads/main/downloads/FRUIT_MAYHEM_Source.zip).

Распакуйте архив и откройте `fruit-mayhem/project.godot` в Godot **4.6.3 Standard**, дождитесь импорта и нажмите F5. В архиве есть полный README, лицензии, отчёт проверок и PowerShell-скрипт сборки.

## Проверки и ограничения

Workflow собирает Windows x64, проверяет игровую сцену и встроенный в EXE пакет ресурсов в Linux, затем публикует ZIP в Releases. Это не заменяет запуск на Windows. Производительность на Intel UHD не измерена.

Это версия **0.1 First Playable**, объём исходного большого ТЗ реализован частично. Полный перечень готовых систем и оставшихся функций — в README проекта.
