# Radar SOCOMB · Tablero

Tablero web del Radar SOCOMB (Bluwall Sistemas Ligeros). Es una sola página (`index.html`) que lee y escribe en Supabase con inicio de sesión. Los datos los alimenta cada viernes la tarea programada del radar; el equipo comercial captura estados, utilidad, revisión de contactos y notas desde aquí.

- Los datos no viven en este repositorio: viven en Supabase, protegidos por reglas de acceso por usuario.
- La clave que aparece en `index.html` es la clave pública (publishable) de Supabase; no da acceso por sí sola.

La página se publica con GitHub Pages desde la rama main.
