# Aplicación Web de Batalla de Cartas

Aplicación web inspirada en un sistema de colección y batalla de cartas tipo Pokémon, desarrollada como proyecto fullstack utilizando Angular y Laravel.

## 🚀 Tecnologías utilizadas

* Frontend: Angular, HTML, CSS, Bootstrap
* Backend: Laravel (PHP)
* Base de datos: MySQL
* Arquitectura: API REST (cliente-servidor)

## 🧠 Funcionalidades

* Autenticación de usuarios (registro e inicio de sesión)
* Sistema de colección de cartas
* Apertura de sobres con generación aleatoria de cartas
* Sistema de puntos
* Persistencia de datos en base de datos relacional
* Comunicación entre frontend y backend mediante API

## 🏗️ Arquitectura

La aplicación sigue una arquitectura cliente-servidor:

* El frontend en Angular gestiona la interfaz y las peticiones HTTP
* El backend en Laravel expone una API REST y gestiona la lógica de negocio
* MySQL se encarga del almacenamiento y persistencia de los datos

## 📸 Capturas

Login:
<img width="482" height="211" alt="image" src="https://github.com/user-attachments/assets/5c96c13c-a69a-4aa9-b8c3-974bad75ecbe" />


## ⚙️ Instalación

### Backend (Laravel)

```bash id="1k9x8c"
cd PokemonBattleBack
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

### Frontend (Angular)

```bash id="9x2b1p"
cd PokemonBattle
npm install
ng serve
```

## 📌 Estado del proyecto

Proyecto finalizado como práctica de desarrollo fullstack.

## 💡 Mejoras futuras

* Mejorar el diseño UI/UX
* Añadir mecánicas de combate más avanzadas
* Mejorar la gestión del estado
* Optimizar el rendimiento de la API
