📊 Mis Finanzas Dashboard - S24 Ultra

Un dashboard financiero moderno y responsivo diseñado para visualizar gastos personales registrados en Notion. Este proyecto utiliza una arquitectura serverless para conectar una interfaz web limpia con la API de Notion.

🚀 Características

Diseño Premium: Estilo "Soft UI" inspirado en interfaces móviles modernas (iOS/OneUI).

Conexión en Tiempo Real: Los datos se obtienen directamente de una base de datos de Notion.

Categorización Automática: El sistema detecta automáticamente categorías (Comida, Gasolina, Streaming) basándose en palabras clave.

Analítica Avanzada: - Proyección de gastos a fin de mes.

Comparativa porcentual con el mes anterior.

Gráficos interactivos (Chart.js).

100% Responsivo: Optimizado para Samsung S24 Ultra y escritorio.

🛠️ Tecnologías Usadas

Frontend: HTML5, Bootstrap 5, Chart.js, Luxon (para fechas).

Backend (Proxy): Cloudflare Workers (para manejar CORS y seguridad de la API Key).

Base de Datos: Notion Database.

⚙️ Instalación y Uso

Clonar el repositorio:

git clone [https://github.com/KarlosMontoya91/Mis-Finanzas-Dash.git](https://github.com/KarlosMontoya91/Mis-Finanzas-Dash.git)


Configuración del Backend:

Este proyecto requiere un intermediario (Proxy) para comunicarse con Notion.

Sube el archivo worker.js (si está incluido) a Cloudflare Workers.

Añade tus credenciales de Notion (NOTION_TOKEN y DATABASE_ID) en las variables de entorno del Worker.

Conectar el Frontend:

Abre index.html en tu editor de código.

Busca la constante API_URL y pega la URL de tu Cloudflare Worker.

¡Listo! Abre el archivo index.html en tu navegador para ver tus finanzas.

📱 Capturas

(Aquí puedes subir capturas de pantalla de tu dashboard una vez esté en GitHub)

Desarrollado por Karlos Montoya