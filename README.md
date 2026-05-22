# CineVault Backend 

API REST desarrollada con Supabase Edge Functions (Deno).

## Endpoints

- POST /auth-api/register — Registro de usuario
- POST /auth-api/login — Login, devuelve JWT
- POST /auth-api/me — Perfil del usuario autenticado
- GET/POST/PUT/DELETE /movies — CRUD de películas
- GET/POST/PUT/DELETE /genres — CRUD de géneros

## Roles

- user: solo lectura del catálogo
- admin: acceso completo al CRUD

## Autor

Gezer Said Flores Murcia
