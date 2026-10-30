# Historial de versiones

## 1.1 — 30/10/2026

- **Enlaces cifrados** con contraseña (AES-256 + HMAC-SHA256, clave por PBKDF2-SHA256 de
  200.000 vueltas). La contraseña se crea la primera vez y se pide en cada arranque.
- Los enlaces guardados por la 1.0 (en texto plano) se cifran solos al crear la contraseña y
  el fichero antiguo se sobrescribe y se borra.
- **Cambiar contraseña…** en Ajustes.
- **Atajo de teclado global** (Ctrl+Alt+P por defecto, elegible en Ajustes): abre el menú
  junto al ratón, se maneja con flechas y Enter y, al copiar, devuelve el foco a la ventana
  donde estabas para pegar directamente.
- Las opciones (atajo, contraseña, inicio con Windows, carpeta de datos) pasan a un submenú
  **Ajustes**.

## 1.0 — 30/10/2026

- Primera versión: icono en la bandeja del sistema con menú de enlaces; un clic copia el texto
  al portapapeles.
- Crear, editar, duplicar, ordenar y borrar enlaces; grupos como submenús; textos de varias
  líneas.
- Iniciar con Windows sin administrador; una sola copia abierta por usuario.
