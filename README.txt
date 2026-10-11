RAPPY MOJI — PROTOTIPO FUNCIONAL v0.2
=====================================

Propósito
---------
Prototipo académico interactivo elaborado para la Actividad 6 de Fundamentos de Diseño de Software. Representa una propuesta para centralizar el registro y seguimiento de domicilios que actualmente se gestionan mediante principalmente WhatsApp y registros manuales.

Alcance del prototipo
---------------------
Incluye:
- Registro de nuevos domicilios.
- Consulta, búsqueda y filtrado de pedidos.
- Asignación simulada de domiciliarios.
- Transiciones de estado: Nuevo → Confirmado → En proceso → Entregado.
- Representación de estados Abandonado y Cancelado.
- Registro simulado de inconvenientes.
- Consulta de domiciliarios e historial.
- Datos ficticios.
- Persistencia local mediante localStorage para la demostración en un navegador.

No incluye:
- Backend ni base de datos centralizada.
- Autenticación o gestión real de usuarios.
- Integración con WhatsApp.
- Pasarela o validación real de pagos.
- Geolocalización ni mapas.
- Notificaciones reales.
- Integración con Excel.
- Seguridad de producción, auditoría y despliegue empresarial.

El estado Abandonado se representa como una transición simulada del proceso actual; El temporizador real de 10 minutos no está implementado.

Cómo usarlo localmente
----------------------
1. Mantén index.html y la carpeta activos en la misma estructura.
2. Abre index.html en Chrome, Edge, Safari o Firefox.
3. No requiere servidor para la demostración básica.
4. Los cambios realizados durante la sesión se guardan en localStorage del navegador.
5. Para reiniciar los datos de demostración, limpie los datos/localStorage del sitio desde las herramientas del navegador.

Imagen del domicilio
-----------------------
La imagen activos/rappi.png es un marcador de posición. Puede reemplazarse por una imagen autorizada manteniendo la misma ruta/nombre, o modificando la ruta en la constante de domiciliarios del archivo index.html.
Para el trabajo académico no deben publicarse fotografías ni datos personales reales sin la autorización correspondiente.

Evaluación con 5 actores
-------------------------
Se recomienda entregar a cada participante solamente una tarea, sin explicarle dónde debe hacer clic. El objetivo es observar si la interfaz comunica por sí misma qué debe hacer.

Tareas sugeridas:
1. Registrador: "Necesita registrar un nuevo domicilio para un cliente. Realiza las acciones que considere necesarias para completar el proceso".
2. Asignar: "El pedido RM-001 está en estado Nuevo. Asígnalo a un domiciliario disponible."
3. En proceso: "El domiciliario ya llegó al establecimiento donde comprará los productos. Actualiza el estado."
4. Entregar: "El domiciliario informa que entregó el pedido. Actualiza el pedido."
5. Excepción: "El domiciliario informa que no encuentra uno de los productos y el cliente no responde. Gestiona la situación de la manera que considere adecuada".

Preguntas posteriores sugeridas:
- ¿Qué fue lo primero que pensaste que debías hacer al entrar al sistema?
- ¿Hubo alguna acción que no supieras dónde encontrar? ¿Cuál?
- ¿Hubo algún momento en el que no supieras qué hacer después?
- ¿Los estados del domicilio te resultaron claros? ¿Alguno te generó confusión?
- ¿La información mostrada en el pedido fue suficiente para realizar la tarea?
- ¿Qué parte fue más fácil de utilizar?
- ¿Qué parte cambiarías?
- Si utilizaras la herramienta durante una jornada de trabajo, ¿qué agregarías o eliminarías?
- Si no te hubiera explicado nada antes de comenzar, ¿crees que habrías podido realizar todo el proceso?

Importante: no se deben fabricar resultados. Registra lo que realmente observa durante las cinco sesiones y usa esos hallazgos para definir la versión v0.2.

Páginas de GitHub
------------
Este prototipo puede publicarse como sitio estático mediante GitHub Pages. Su publicación no lo convierte en una aplicación productiva: continúa siendo un prototipo académico estático que ejecuta HTML/CSS/JavaScript en el navegador.

Pasos generales:
1. Crea un repositorio, por ejemplo: rappy-moji-prototipo.
2. Sube index.html y la carpeta de activos.
3. En Configuración → Páginas, configure el despliegue desde la rama principal (o el método disponible en la cuenta).
4. GitHub generará una URL de proyecto similar a: https://TU-USUARIO.github.io/rappy-moji-prototipo/
5. Pruebe la URL en una ventana de incógnito antes de compartirla.
6. No publique datos personales, fotografías no autorizadas, credenciales ni información real de clientes/domiciliarios.

Versionado académico sugerido
-----------------------------
v0.1 — Prototipo inicial para evaluación.
v0.1 + evaluación — Observaciones de 5 actores.
v0.2 — Ajustes realizados a partir de los hallazgos.
Actividad 6 — Socialización y nueva evaluación/refinamiento, según las instrucciones de la asignatura.

Uso de IA
---------
ChatGPT fue utilizado como herramienta de apoyo para estructurar, generar y revisar partes del código HTML/CSS/JavaScript del prototipo. Las decisiones sobre el problema, usuarios, requisitos, tareas de evaluación y conclusiones deben sustentarse en el caso Rappy Moji, las observaciones reales y la bibliografía académica de la asignatura.
