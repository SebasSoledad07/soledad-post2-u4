# Proyecto de Registro de Usuario — Unidad 4

Este proyecto consiste en la implementación de un formulario de registro de usuario con validación completa del lado del cliente. Se integra el uso de la Constraint Validation API nativa del navegador con validaciones personalizadas mediante JavaScript (ES6) para ofrecer una experiencia de usuario fluida y segura.

## 🚀 Objetivo

Desarrollar una aplicación web que gestione el registro de usuarios, aplicando:

- Validación manual y nativa combinada.
- Retroalimentación visual inmediata (tiempo real) mediante eventos como blur e input.
- Control estricto del evento submit para prevenir envíos de datos incorrectos.
- Uso de expresiones regulares para formatos complejos y evaluación de fortaleza de contraseñas.

## 🛠️ Tecnologías y Herramientas

- **HTML5:** Estructura semántica del formulario y atributos de validación nativa (required, minlength, pattern).
- **CSS3:** Estilos para estados válidos/inválidos y control de visibilidad de mensajes de error.
- **JavaScript (ES6+):** Manipulación del DOM, manejo de eventos, template literals, arrow functions y destructuring.

## 📂 Estructura del Repositorio

El proyecto mantiene la siguiente organización de archivos:

- `index.html`: Estructura del formulario y contenedores de error.
- `styles.css`: Estilos visuales y clases de estado (.visible, .invalido, .valido).
- `validacion.js`: Lógica de validación, manejo de eventos e indicador de fortaleza.

## 🚀 Instrucciones de Ejecución

Para visualizar este proyecto de forma local:

1. Clone el repositorio en su máquina local.
2. Abra la carpeta raíz con **Visual Studio Code**.
3. Localice el archivo `index.html`.
4. Haga clic derecho y seleccione **"Open with Live Server"**.

## 📝 Checkpoints de Validación

A lo largo del desarrollo se verificaron los siguientes hitos:

- **Validación en Envío:** Al intentar registrarse sin llenar campos, se activan los mensajes de error específicos y bordes rojos.
- **Tiempo Real:** Al abandonar un campo (blur) con datos incorrectos, el error aparece inmediatamente.
- **Confirmación de Contraseñas:** Validación lógica que asegura que ambos campos de contraseña coincidan exactamente.
- **Fortaleza de Contraseña:** Un indicador dinámico evalúa si la clave es "Débil", "Regular", "Buena" o "Fuerte" según su longitud y diversidad de caracteres.
- **Exito:** Al completar todo correctamente, se muestra un mensaje de bienvenida y el formulario se reinicia automáticamente tras 2 segundos.
