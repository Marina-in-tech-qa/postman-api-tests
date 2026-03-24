# API Testing (Postman)

## 📌 О проекте
В данном репозитории представлены примеры тестирования API с использованием Postman.

## 🔧 Инструменты
- Postman
- GitHub

---

## 📬 Что реализовано

- Отправка GET-запросов
- Проверка статус-кодов
- Написание автотестов (Tests)

Пример теста:
```javascript
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
