# HÁBITOS ATÓMICOS - Backend
API REST desarrollada con Express.js y MongoDB Atlas para la gestión de hábitos.

Este proyecto corresponde al desarrollo del backend de una aplicación para la gestión de hábitos basado en el libro "Hábitos Atómicos" de James Clear. Permite crear, editar, eliminar y consultar hábitos almacenados en una base de datos MongoDB.

## Tecnologías utilizadas:
- Node.js
- Express.js
- MongoDB Atlas

## Requisitos
- Node.js
- MongoDB Atlas
- Git

## Instalación
1. Clonar el repositorio git clone <https://github.com/AnaIcu/HabitosAtomicos_backend_25004137/tree/semana4>
2. Entrar al proyecto cd PROYECTO_25004137
3. Instalar dependencias: npm install
4. Crear archivo .env:
MONGO_URI=dirección base de datos en Mongo
PORT=3001
JWT_SECRET=

## Ejecutar el proyecto
npm start
(El servidor se ejecuta en http://localhost:3001)

## Endpoints
GET /habitos
POST /habitos
PUT /habitos/:id
DELETE /habitos/:id
