# pdd_russia

Описание:

Репозиторий содержит экзаменационные вопросы для получения водительского удостоверения в РФ.
Вопросы сгруппированы по билетам от 1 до 40

* questions.json содержит список вопросов с разбивкой по билетам в формате JSON.
* в папке images/ находятся сопутствующие графические материалы. 

```json
[
  {
    "title": "Вопрос 1",
    "ticket_number": "Билет 1",
    "image": "./images/ticket_1/1_1.jpg",
    "question": "В каком случае водитель совершит вынужденную остановку?",
    "answers": [
      {
        "answer_text": "Остановившись непосредственно перед пешеходным переходом, чтобы уступить дорогу пешеходу",
        "is_correct": false
      },
      {
        "answer_text": "Остановившись на проезжей части из-за технической неисправности транспортного средства",
        "is_correct": true
      },
      {
        "answer_text": "В обоих перечисленных случаях",
        "is_correct": false
      }
    ],
    "correct_answer": "Правильный ответ: 2",
    "answer_tip": "«Вынужденная остановка» - прекращение движения транспортного средства, связанное с его технической неисправностью, опасностью, создаваемой перевозимым грузом, состоянием водителя (пассажира) или появления препятствия на дороге. (Пункт 1.2 ПДД, термин «Вынужденная остановка»)"
  },
```