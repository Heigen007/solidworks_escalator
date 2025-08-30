# 🏗️ Escalator Design Project | Проект Эскалатора

[![SOLIDWORKS](https://img.shields.io/badge/SOLIDWORKS-Compatible-red.svg)](https://www.solidworks.com/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## 📋 Описание проекта | Project Description

**Русский:**
Данный проект представляет собой полную 3D модель эскалатора, разработанную в SOLIDWORKS. Проект включает в себя все необходимые детали, сборки и чертежи для понимания конструкции эскалатора.

**English:**
This project presents a complete 3D model of an escalator developed in SOLIDWORKS. The project includes all necessary parts, assemblies, and drawings to understand the escalator construction.

## 🎯 Демонстрация | Demo

![Escalator Animation](media/Gif%20(1).gif)
![Assembly Process](media/Gif%20(2).gif)

## 📁 Структура проекта | Project Structure

```
solidworks_escalator/
├── 📂 parts/                     # Детали | Parts
│   ├── Chain.SLDPRT             # Цепь
│   ├── Chain assemble part.SLDPRT # Часть сборки цепи
│   ├── Front axle of the step.SLDPRT # Передняя ось ступени
│   ├── Rear axle of the step.SLDPRT  # Задняя ось ступени
│   ├── Gear.SLDPRT              # Шестерня
│   ├── Gear wheel.SLDPRT        # Зубчатое колесо
│   ├── Pin.SLDPRT               # Штифт
│   ├── SidePartOdEscalator.SLDPRT # Боковая часть эскалатора
│   ├── Skelet.SLDPRT            # Каркас
│   ├── Step.SLDPRT              # Ступень
│   ├── Step wheel.SLDPRT        # Колесо ступени
│   ├── Step assemble part.SLDPRT # Часть сборки ступени
│   └── UpperAxle.SLDPRT         # Верхняя ось
├── 📂 assemblies/                # Сборки | Assemblies
│   ├── 1v assemble video.SLDASM  # Видео сборка (версия 1)
│   ├── Chain assemble.SLDASM     # Сборка цепи
│   ├── final with chain.SLDASM   # Финальная сборка с цепью
│   └── Step assemble.SLDASM      # Сборка ступени
├── 📂 drawings/                  # Чертежи | Technical Drawings
│   ├── Chain.SLDDRW             # Чертеж цепи
│   ├── Gear.SLDDRW              # Чертеж шестерни
│   ├── SidePartOdEscalator.SLDDRW # Чертеж боковой части
│   ├── Skelet.SLDDRW            # Чертеж каркаса
│   └── Step assemble part.SLDDRW # Чертеж сборки ступени
├── 📂 media/                     # Медиа файлы | Media Files
│   ├── Gif (1).gif              # Анимация работы эскалатора
│   └── Gif (2).gif              # Анимация сборки
├── 📂 documentation/             # Документация | Documentation
│   ├── SOLIDWORKS.pptx          # Презентация проекта
│   └── Таблица_компонентов_эскалатора.docx # Таблица компонентов
└── README.md                     # Этот файл
```

## 🔧 Основные компоненты | Main Components

### Механические детали | Mechanical Parts
- **Ступени (Steps)** - основные элементы для перемещения пассажиров
- **Цепной привод (Chain Drive)** - система передачи движения
- **Шестерни (Gears)** - элементы трансмиссии
- **Оси (Axles)** - опорные и приводные валы
- **Каркас (Frame)** - несущая конструкция

### Сборочные узлы | Assembly Units
- **Сборка ступеней** - комплексный узел ступени с осями и колесами
- **Цепная передача** - механизм передачи движения
- **Финальная сборка** - полная конструкция эскалатора

## 🚀 Начало работы | Getting Started

### Требования | Requirements
- SOLIDWORKS 2018 или новее
- Минимум 8 GB RAM
- Дискретная видеокарта (рекомендуется)

### Установка | Installation
1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/Heigen007/solidworks_escalator.git
   ```
2. Откройте файл `final with chain.SLDASM` в SOLIDWORKS для просмотра полной сборки

### Порядок открытия файлов | File Opening Order
1. Сначала откройте все файлы из папки `parts/`
2. Затем откройте сборки из папки `assemblies/` в следующем порядке:
   - `Step assemble.SLDASM`
   - `Chain assemble.SLDASM`
   - `final with chain.SLDASM`

## 📐 Технические характеристики | Technical Specifications

| Параметр | Значение |
|----------|----------|
| Общая длина | ~5000 мм |
| Ширина ступени | ~1000 мм |
| Высота подъема | ~3000 мм |
| Количество ступеней | 20-25 шт |
| Скорость движения | 0.5 м/с |

## 🎓 Образовательная ценность | Educational Value

Этот проект демонстрирует:
- **Механическое проектирование** - принципы создания сложных механизмов
- **Сборочное моделирование** - взаимодействие множественных компонентов
- **Техническое черчение** - создание рабочих чертежей
- **Кинематический анализ** - изучение движения механизмов

## 📊 Статистика проекта | Project Statistics

- **Количество деталей:** 13
- **Количество сборок:** 4
- **Количество чертежей:** 5
- **Общий размер файлов:** ~50 MB

## 🤝 Вклад в проект | Contributing

Приветствуются любые улучшения проекта:
- Оптимизация деталей
- Добавление новых компонентов
- Улучшение сборок
- Исправление ошибок

## 📞 Контакты | Contact

- **GitHub:** [Heigen007](https://github.com/Heigen007)
- **Project Repository:** [solidworks_escalator](https://github.com/Heigen007/solidworks_escalator)

## 📄 Лицензия | License

Этот проект распространяется под лицензией MIT. См. файл `LICENSE` для подробностей.

---

⭐ **Понравился проект? Поставьте звезду!** | **Like the project? Give it a star!**

📚 **Образовательный проект** | **Educational Project**

🛠️ **Создано с помощью SOLIDWORKS** | **Made with SOLIDWORKS**
