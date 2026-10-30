25 LATIDOS — Carlos & Astrid

Aplicación web instalable (PWA) sin dependencias externas.

Para probar localmente desde una computadora:
  cd 25_latidos
  python -m http.server 8000
  Abrir http://localhost:8000

Para compartir con Astrid por enlace y permitir instalación en Android/iPhone:
  Publicar el contenido de esta carpeta en un hosting HTTPS (GitHub Pages, Netlify, Cloudflare Pages).
  Compartir la URL. En iPhone: Safari > Compartir > Agregar a pantalla de inicio.
  En Android: navegador > Instalar aplicación / Agregar a pantalla de inicio.

Los datos se guardan SOLO en el navegador de cada dispositivo (localStorage), no se sincronizan.
Revisar y personalizar las preguntas en la constante Q de index.html antes de publicar.
El juego no solicita ni almacena fotografías, ni transmite datos a un servidor.
