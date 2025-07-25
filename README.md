# 📚 Демонстрационные ML/CV/NLP проекты

В этом репозитории собраны четыре учебных проекта по анализу данных, машинному обучению и компьютерному зрению. Каждый проект оформлен в отдельной папке и снабжён подробным `README.md` и Jupyter-ноутбуком.

---

## 🚀 Список проектов

| №  | Проект                                            | Описание                                                                                               | Папка                          |
|---:|:--------------------------------------------------|:-------------------------------------------------------------------------------------------------------|:-------------------------------|
| 1. | Прогноз заказов такси                             | Модель временных рядов для предсказания числа заказов такси на следующий час (RMSE ≤ 48).              | `time_series`                  |
| 2. | Классификация токсичных комментариев              | NLP-проект: бинарная классификация правок/комментариев на токсичные и нетоксичные (F1 ≥ 0.75).          | `toxic-classification`         |
| 3. | Оценка возраста по фотографии                     | CV-модель: регрессия возраста по фотографии с оптимизацией MAE (средняя абсолютная ошибка ≈ 5.95 лет). | `age-estimation`               |
| 4. | Поиск изображений по запросу                      | Демонстрационная multimodal-система: оценка соответствия «текст ↔ изображение» (0–1).                   | `image-search-demo`            |

---

## 🗂️ Структура репозитория

- **time_series/**  
  └─ `README.md`  
  └─ `time_series.ipynb`  
  └─ `requirements.txt`

- **toxic-classification/**  
  └─ `README.md`  
  └─ `nlp_project.ipynb`  
  └─ `requirements.txt`

- **age-estimation/**  
  └─ `README.md`  
  └─ `CV_project.ipynb`  
  └─ `requirements.txt`

- **image-search-demo/**  
  └─ `README.md`  
  └─ `something.ipynb`  
  └─ `requirements.txt`
