# Практика в Jira

Все 5 багов, найденных при тестировании [playground.learnqa.ru/puzzle/triangle](https://playground.learnqa.ru/puzzle/triangle) (см. [bug-reports.md](.learnqa-triangle/bug-reports.md)), оформлены как задачи типа **Баг** в Jira (Kanban-доска, проект **KAN**), с полями Summary, Description (окружение, предусловия, шаги воспроизведения, фактический/ожидаемый результат, Severity), Priority, метками и вложениями.

## Доска

Задачи распределены по статусам жизненного цикла (К выполнению → В работе → На проверке → Готово), демонстрируя рабочий процесс, а не просто список.

![Kanban-доска со всеми задачами](./screenshots-jira/jira-board.png)

## Задачи

### KAN-1 — Отсутствие оповещения об ошибке при вводе символа "?"
Статус: На проверке · Priority: Low · Метка: `learnqa-triangle`

![KAN-1](./screenshots-jira/jira-kan1.png)

### KAN-2 — Отсутствие ограничения на количество отправок писем на один email
Статус: Готово · Priority: Medium

![KAN-2](./screenshots-jira/jira-kan2.png)

### KAN-3 — Форма для ввода значений неправильно работает с нецелыми числами
Статус: В работе · Priority: High

![KAN-3](./screenshots-jira/jira-kan3.png)

### KAN-4 — Программа определяет треугольник с значениями сторон 0 как равносторонний
Статус: К выполнению · Priority: Low

![KAN-4](./screenshots-jira/jira-kan4.png)

### KAN-5 — Форма ввода значений сторон треугольника не валидирует поле C
Статус: В работе · Priority: Low

![KAN-5](./screenshots-jira/jira-kan5.png)
