# 🔌 API Testing — Postman Collection

<div align="center">
  
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Newman](https://img.shields.io/badge/Newman-00B9F1?style=for-the-badge&logo=postman&logoColor=white)
![Allure](https://img.shields.io/badge/Allure_Report-FF6C37?style=for-the-badge&logo=testinglibrary&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

</div>

---

## 📋 О проекте

Коллекция API-тестов в **Postman** с проверкой JSON-схем, query-параметров и методов HTTP (GET, POST, PUT, DELETE). Тестируемый ресурс — [send-request.me](https://send-request.me/) через Swagger.

---

## 🚀 Быстрый старт

### Установка

```bash
# 1. Клонируйте репозиторий
git clone https://github.com/sonyfrid/testAPI.git

# 2. Импортируйте коллекцию в Postman
# File → Import → Выберите файлы из репозитория

# 3. Готово! Можно запускать тесты
```
## 📊 Примеры запросов в Postman

### 1️⃣ JSON Schema

For ease of testing, JSON schemas are pre-written here.

![JSON Schema](https://github.com/sonyfrid/image/blob/main/1.png?raw=true)

---

### 2️⃣ GET — Получение списка компаний

Here we see the end point check. I send a GET request with query parameters to get a list of companies. Below is a visualization of the response body.

![GET Request](https://github.com/sonyfrid/image/blob/main/3.png?raw=true)

---

### 3️⃣ POST — Создание пользователя

The user has been successfully created here. The check passed because the response matches the JSON schema.

![POST Request](https://github.com/sonyfrid/image/blob/main/4.png?raw=true)

---

### 4️⃣ PUT — Обновление данных

We change our Scrooge to Pascal using the PUT method.

![PUT Request](https://github.com/sonyfrid/image/blob/main/5.png?raw=true)

---

### 5️⃣ DELETE — Удаление пользователя

Deleting a user. The response does not match the JSON schema.

![DELETE Request](https://github.com/sonyfrid/image/blob/main/6.png?raw=true)

---

### 6️⃣ Тесты — Проверка одинарных кавычек

An example of tests for checking single quotes.

![Single Quotes Test](https://github.com/sonyfrid/image/blob/main/8.png?raw=true)

---

### 7️⃣ Тесты — Валидация длины значения

Example of tests checking the length of the "company_id" value.

![Length Validation](https://github.com/sonyfrid/image/blob/main/8.png?raw=true)

---

### 8️⃣ Отчёты Newman + Allure

Collection run report from Newman and Allure.

![Newman Report](https://github.com/sonyfrid/image/blob/main/Monosnap+Newman+Summary+Report+-+Google+Chrome+202%20(1).png?raw=true)

![Allure Report](https://github.com/sonyfrid/image/blob/main/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82-11-10-2023%2013_28_28.png?raw=true)
