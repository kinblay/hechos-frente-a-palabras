# Hechos frente a palabras

Herramienta independiente para las elecciones generales del 29 de noviembre de 2026: test de afinidad en 30 tesis, qué ha dicho y votado cada partido (citas literales con su fuente), compromisos de campaña y pactómetro.

- `index.html`: la web completa (sin dependencias propias; tipografías de Google Fonts y three.js desde cdnjs solo para la vista 3D).
- `datos.json`: citas, votaciones y compromisos. Se regenera desde la base de datos de trabajo; la fecha de los datos aparece en la cabecera de la web.
- Barómetro anónimo (general y por grupos): servidor Supabase en la UE. La web solo puede llamar a funciones que devuelven totales; no puede leer respuestas individuales.

No es un sitio oficial ni está vinculado a ningún partido. No recomienda voto.
