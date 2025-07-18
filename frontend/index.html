const express = require('express');
const cors = require('cors'); // Necesario para permitir solicitudes desde el frontend

const app = express();
// Usa process.env.PORT para que entornos en la nube (como Codespaces) asignen el puerto dinámicamente.
// Si no hay variable de entorno (ej. ejecutando localmente sin configuración específica), usará 5050.
const PORT = process.env.PORT || 5050;

app.use(cors()); // Habilita CORS para permitir que tu frontend (en otro puerto/dominio) se conecte
app.use(express.json()); // Middleware para parsear el cuerpo de las solicitudes JSON (si envías datos)

// Datos en memoria para simular una base de datos.
// Estos datos se reinician cada vez que el servidor se reinicia.
let publicaciones = [
  { id: 1, titulo: 'Primera publicación', descripcion: 'Contenido de la primera publicación desde el backend' },
  { id: 2, titulo: 'Segunda publicación', descripcion: 'Contenido de la segunda publicación desde el backend' },
];

// Ruta Raíz (GET /)
// Propósito: Para verificar rápidamente que el servidor está activo y respondiendo.
app.get('/', (req, res) => {
  res.send('Backend de HabitaZona funcionando correctamente!');
});

// Ruta para obtener todas las publicaciones (GET /api/publicaciones)
// Propósito: Devolver la lista completa de publicaciones disponibles.
app.get('/api/publicaciones', (req, res) => {
  res.json(publicaciones);
});

// El servidor empieza a escuchar en el puerto definido
app.listen(PORT, () => {
  console.log(`Servidor corriendo en el puerto ${PORT}`);
});
