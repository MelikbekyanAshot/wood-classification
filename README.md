# Выпускная квалификационная работа по программе цифровой кафедры РТУ МИРЭА

## Постановка задачи
Обучить нейронную сеть для классификации изображений, содержащих спилы бревен, по трем категориям сортности:
- 1 и 2 сорт
- 3 сорт
- дрова

Примеры показаны на изображении ниже

<img src="assets/wood_examples.png" alt="wood examples" width="300"/>

## Решение
### ViT
Лучшим решением поставленной задачи является дообучение визуального трансформера на имеющемся наборе данных.

### Валидация результатов
График изменения метрики F1-score на валидационной выборке

<img src="assets/vit_f1_val.png" alt="ViT F1-score on val dataset" width="500"/>

Матрица ошибок

<img src="assets/confussion_matrix.png" alt="Confussion matrix" width="500"/>

Пример верно предсказанных классов сортности

<img src="assets/predicted_labels.png" alt="Predicted" width="500"/>

Веса модели доступны по ссылке: https://drive.google.com/drive/folders/1V-vAoji3s9dBsNzYbXSDV8v84obEp4aL?usp=drive_link
