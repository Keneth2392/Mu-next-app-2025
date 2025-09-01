KR Bingo Cash — Capacitor (Android + iOS) con lista de jugadores
=================================================================
- Multijugador en vivo con Firebase.
- Voz clara en español, 5 cartones en pantalla, FREE marcado, Ambo/Triple solo 1 ganador.
- Lista de jugadores conectados (con "online" por latido/heartbeat).

Cómo abrir en Android Studio / Xcode
------------------------------------
1) Requisitos: Node.js, Android Studio, Xcode (en macOS) si compilas iOS.
2) En la raíz del ZIP:
   npm install
   npm run cap:init   (si te lo pide)
   npm run cap:sync

Android:
   npm run android
   -> Generar APK/AAB desde Build > Generate Signed Bundle/APK

iOS:
   npm run ios
   -> Selecciona tu equipo y compila al iPhone

Web/PWA local:
   npm run dev
   -> http://localhost:5173

Nota: Firestore necesita que habilites las reglas en modo test o definas reglas seguras.
