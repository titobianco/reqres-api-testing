# Reqres API Testing with Postman

This project contains a collection of tests for the public API [Reqres](https://reqres.in), created using Postman.

## 🔍 What’s being tested?

- Authentication via `POST /login`
- Token handling (simulated)
- Error validation (400 responses)
- User retrieval via `GET`
- Assertion automation using Postman test scripts

## ✅ Included test cases

| Method | Endpoint            | Description                     | Expected Result            |
|--------|---------------------|----------------------------------|----------------------------|
| GET    | `/api/users?page=2` | List users                       | 200 OK + user list         |
| POST   | `/api/login`        | Login with credentials           | 200 OK + token             |
| GET    | `/api/users/2`      | Get user (simulated token)       | 200 OK                     |
| POST   | `/api/login` (invalid) | Missing password              | 400 Bad Request            |

## ⚙️ How to use this collection

1. Import the `.postman_collection.json` file into Postman
2. Run each request manually or use the Runner
3. Review the tests in the “Tests” tab of each request
4. Feel free to customize it for your own projects!

---

This project was part of my API Testing training with Postman.


--------------------------------------------------------//--------------------------------------------------------

# Reqres API Testing with Postman

Este proyecto contiene una colección de pruebas para la API pública [Reqres](https://reqres.in), utilizando Postman.

## 🔧 ¿Qué se testea?

- Autenticación con `POST /login`
- Manejo de tokens (simulado)
- Validación de errores (400)
- Obtención de usuarios con `GET`
- Automatización de assertions con tests de Postman

## 🧪 Casos de prueba incluidos

| Método | Endpoint                  | Caso                         | Resultado esperado |
|--------|---------------------------|------------------------------|--------------------|
| GET    | `/api/users?page=2`       | Listar usuarios              | 200 OK + lista     |
| POST   | `/api/login`              | Login con credenciales       | 200 OK + token     |
| GET    | `/api/users/2`            | Obtener usuario (token sim.) | 200 OK             |
| POST   | `/api/login` (inválido)   | Falta password               | 400 Bad Request    |

## 📦 Cómo usar esta colección

1. Importá el archivo `.postman_collection.json` en Postman
2. Ejecutá cada request manualmente o en Runner
3. Revisá los tests en la pestaña `Tests` de cada request
4. ¡Personalizalo para tus propios proyectos!

---

Este proyecto fue realizado como parte de mi entrenamiento en API Testing con Postman 💻
