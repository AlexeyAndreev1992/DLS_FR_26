# Face Recognition Using Deep Metric Learning

Дипломный проект по исследованию методов распознавания лиц с использованием глубокого обучения и обучения метрического пространства.

## Описание проекта

Цель проекта — исследование современных методов распознавания лиц на датасете CelebA и сравнение различных функций потерь при обучении нейронной сети.

В работе исследуются:

- Cross-Entropy Loss
- Triplet Loss
- ArcFace Loss


---

## Структура проекта

```
.
├── Podgotovka_dataseta_fin.ipynb             # Подготовка датасета
├── CE_loss_validation_fin.ipynb              # Обучение с Cross-Entropy
├── Triplet_Loss_Face_Recognition_dop1.ipynb  # Реализация Triplet Loss
├── ArcFace_Triplet_Loss_Training_dop2.ipynb  # Реализация Triplet Loss + ArcFace
├── FaceRecognition_Issledovanie_dop3.ipynb   # Дополнительная часть диплома с исследованием
├── face_recognition_full_pipeline.ipynb      # Реализация пайплайна
├── aligned_dataset_simple.part*.rar          # Подготовленный датасет
├── models.part*.rar                          # Обученные модели
└── README.md
```

---

## Датасет

Используется датасет **CelebA**.

Для ускорения обучения лица предварительно:

- обнаружены;
- выровнены;
- обрезаны;
- сохранены в формате JPG.

Из-за ограничений GitHub датасет разбит на несколько архивов:

```
aligned_dataset_simple.part1.rar
aligned_dataset_simple.part2.rar
aligned_dataset_simple.part3.rar
aligned_dataset_simple.part4.rar
```

После распаковки получается папка:

```
aligned_faces_all/
```

---

## Обучение



Исследованы следующие функции потерь:

- Cross-Entropy Loss
- Triplet Loss
- ArcFace Loss

---

## Результаты

В проекте реализованы:

- обучение моделей;
- построение embedding-пространства;
- поиск похожих лиц;
- Rank-1 Identification;
- Verification;
- подбор оптимального cosine threshold;
- построение centroid gallery.

---

## Используемые библиотеки

- Python 3.11
- PyTorch
- Torchvision
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Pillow

---

## Автор

Алексей Андреев

Дипломная работа  
2026