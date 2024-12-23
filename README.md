# STM32-ARM-Toolchain-VSCode

**ARM Toolchain** — это набор инструментов для разработки программ под микроконтроллеры ARM. Включает всё необходимое для написания, компиляции, сборки, отладки и прошивки программ.

---

## Основные компоненты

### 1. Компилятор и сборка
- **`arm-none-eabi-gcc`**: Компиляция C/C++ кода.
- **`arm-none-eabi-as`**: Ассемблер для кода на языке ассемблера.
- **`arm-none-eabi-ld`**: Линковщик для объединения объектных файлов.

### 2. Утилиты для бинарных файлов
- **`arm-none-eabi-objcopy`**: Конвертация ELF в бинарный (`.bin`) или Intel Hex (`.hex`).
- **`arm-none-eabi-objdump`**: Анализ ELF-файлов.
- **`arm-none-eabi-size`**: Отображение размера секций (text, data, bss).

### 3. Отладка
- **`arm-none-eabi-gdb`**: Отладка программы на микроконтроллере.
---

## Полезные утилиты

- **OpenOCD**:  
  Позволяет работать с микроконтроллером через интерфейсы SWD/JTAG для прошивки и отладки.

- **ST-Link Utility**:  
  Инструменты от STMicroelectronics для загрузки программ на микроконтроллеры STM32.
  
- **CMake**:  
  Кроссплатформенная система сборки. Генерирует файлы для Make, Ninja или других систем на основе `CMakeLists.txt`. Удобна для работы с крупными проектами.

---
