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
