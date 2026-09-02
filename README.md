# CGCNN для предсказания свойств материалов

Реализация Crystal Graph Convolutional Neural Networks (CGCNN) на основе работы Tian Xie и Jeffrey C. Grossman.

## Содержание

- `M3_CGCNN_Practice.ipynb` — обучающий ноутбук с разбором архитектуры, построением кристаллических графов и обучением упрощенной модели
- `M3_CGCNN_Hometask.ipynb` — домашнее задание по обучению полной модели CGCNN

## Установка

```bash
pip install pymatgen ase mp-api mendeleev pandas torch scikit-learn matplotlib

Для работы с Materials Project API требуется API-ключ. Вставьте его в переменную API_KEY.
