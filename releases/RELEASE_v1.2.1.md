# MegaLadder Stats Overlay v1.2.1

## 🇷🇺 Русский

### 🐛 Исправления

*   **Исправлен баг с подсчётом убийств**:
    *   Устранена проблема, из-за которой счётчик убийств показывал неправильные значения в Full Focus Mode.
    *   Парсинг чисел теперь корректно обрабатывает строки вида "100 (+50)" — извлекается только основное число.

*   **Овертайм отключён в Full Focus Mode**:
    *   Таймер овертайма автоматически скрывается в режиме полного фокуса, как и было задумано.

*   **Исправлено отображение MMR**:
    *   Обновлён селектор для парсинга MMR в соответствии с новой HTML-структурой сайта.
    *   MMR теперь отображается с правильным цветом ранга.

### 🆕 Новые функции

*   **Значок ранга MMR (MMR Badge)**:
    *   Новая настройка "Показать значок ранга" в панели видимости.
    *   Рядом с MMR теперь отображается иконка ранга игрока
    *   Поддержка для обоих игроков.

---

## 🇬🇧 English

### 🐛 Bug Fixes

*   **Fixed kill count calculation bug**:
    *   Resolved issue where kill counter showed incorrect values in Full Focus Mode.
    *   Number parsing now correctly handles strings like "100 (+50)" — only the main number is extracted.

*   **Overtime disabled in Full Focus Mode**:
    *   Overtime timer is now automatically hidden in full focus mode, as intended.

*   **Fixed MMR display**:
    *   Updated selector for MMR parsing to match new site HTML structure.
    *   MMR now displays with correct rank color.

### 🆕 New Features

*   **MMR Rank Badge**:
    *   New "Show Rank Badge" setting in visibility panel.
    *   Player rank icon now displays next to MMR.
    *   Support for both players.
