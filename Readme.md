1. Прогоняем отладку трех вариантов
<img width="974" height="328" alt="image" src="https://github.com/user-attachments/assets/8756ead2-2c37-414f-ab85-40c5b09d6041" />
<img width="974" height="455" alt="image" src="https://github.com/user-attachments/assets/971efcfa-f5c7-4d1d-b3f4-5f8a280bc4c4" />

Без синхронизации происходит гонка данных и счётчик считает неправильно.
Lock и Mutex обеспечивают взаимное исключение и правильный результат, но увеличивают время из-за накладных расходов синхронизации.

