# Plates Classifier

Классификация чистых и грязных тарелок. Решение для [Kaggle Plates v2](https://www.kaggle.com/competitions/platesv2).

## Задача
Бинарная классификация изображений тарелок: clean (0) vs dirty (1).

## 📊 Данные
- **Train**: 40 изображений (20 clean + 20 dirty)
- **Test**: ~300+ изображений
- **Метрика**: Accuracy

## 🛠️ Технологический стек
[![Tech Stack](https://skillicons.dev/icons?i=python,pytorch,lightning,opencv&theme=dark)](https://skillicons.dev)

## План работ:

1. EDA (разведочный анализ)
        ↓
2. Бейзлайн (простая модель)
        ↓
3. Transfer Learning (основной подход)
        ↓
4. Аугментации (борьба с переобучением)
        ↓
5. Кросс-валидация (оценка качества)
        ↓
6. Финальная настройка и submission

## Быстрый старт

### 1. Установка зависимостей
```bash
pip install -r requirements.txt