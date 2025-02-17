# YANDEX-AIDAO-1st-stage
Международная олимпиада по искусственному интеллекту и анализу данных от *Яндекса* и *ФКН ВШЭ*.

## Track 1: Идентификация личности по данным fMRI
- **Задача**: Определить, принадлежат ли два временных ряда fMRI одному человеку.
- **Данные**: 20 субъектов × 16 представлений (2 атласа × 2 стратегии сглаживания × 2 сегмента × 2 последовательности).
- **Методы**: Корреляционный анализ, кластеризация, выделение паттернов функциональной связности.
- **Результат**: Файл `submission__.csv` с предсказаниями меток для каждого объекта. Метрика ARI близка к 1.0.

## Track 2: Классификация состояний покоя (открытые/закрытые глаза)
- **Задача**: Классифицировать состояния покоя на основе fMRI данных.
- **Данные**: Датасеты BNU и IHB RAS (47+95, 10+10, 20+20, 117+117 участников).
- **Методы**: CatBoost, ансамбль моделей (CatBoost + логистическая регрессия + перцептрон), PCA для снижения размерности.
- **Результат**: Accuracy на тесте — 0.95, F1-score — 0.95238.

**Команда** : JULEBINO TEAM  
**Участники** : Белянинов Илья, Ешеров Амин, Соколанов Алексей.
