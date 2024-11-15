
bonaVientos
bonaVientos es una aplicación desarrollada con Node.js, Express, NPM, Axios y EJS que te ayuda a determinar si el viento está a favor o en contra en función de tu ruta (por ahora, entre el centro y la universidad) en la ciudad de Río Cuarto.

Cómo usar
Clonar el repositorio:

Abre Git Bash y ejecuta el siguiente comando para clonar el repositorio:

bash
Copiar código
git clone https://github.com/alejobonavia003/bonaVientos.git
Instalar dependencias:

Navega hasta la carpeta del proyecto en tu terminal o PowerShell, y luego instala las dependencias con:

bash
Copiar código
npm install
Iniciar el servidor:

Una vez que las dependencias estén instaladas, inicia el servidor con el siguiente comando:

bash
Copiar código
node index.js
Acceder a la aplicación:

Abre tu navegador y entra a la siguiente dirección:

arduino
Copiar código
http://localhost:3000
Descripción
Esta aplicación proporciona información meteorológica en tiempo real para la ciudad de Río Cuarto. Los usuarios pueden elegir un origen y un destino (actualmente solo disponible entre Centro y Universidad) y, al hacer clic en "Calcular", se mostrará si el viento sopla a favor o en contra para esa ruta.

Objetivo
El objetivo de esta aplicación es resolver un problema personal: determinar si tengo viento a favor o en contra al ir o volver del centro. A menudo, me da pereza revisar la dirección del viento y muchas veces me baso solo en observar las hojas de los árboles para hacerme una idea del viento, ¡pero eso no siempre es confiable!

Este proyecto está pensado para facilitar la toma de decisiones sobre la hora de salida, sin tener que depender de la observación del viento, y es una forma divertida de aplicar mis conocimientos de programación.

Aunque probablemente sea más útil para mí que para otra persona, este es un proyecto que también tiene valor como experiencia personal y como un pequeño proyecto para @yu_angela.

Tecnologías utilizadas
Node.js: Entorno de ejecución para JavaScript en el servidor.
Express: Framework de Node.js para facilitar el manejo de rutas y servidores.
Axios: Librería para hacer solicitudes HTTP y obtener datos de la API del clima.
EJS: Motor de plantillas para generar HTML dinámico en el servidor.
¡Gracias por visitar el repositorio y por el interés en el proyecto! Si tienes alguna pregunta o sugerencia, no dudes en abrir un issue o enviar un pull request.