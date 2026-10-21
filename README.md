# Simulacro Nacional 2026 · Colombia

App ciudadana (PWA) para **preparar, ejecutar y reportar** el Simulacro Nacional de Respuesta a Emergencias de Colombia — **miércoles 21 de octubre de 2026**, 10:00 a.m. (ciudadanía, familias, colegios, empresas) y 2:00 p.m. (alcaldías y gobernaciones), convocado por la UNGRD mediante la Circular 079 de 2026.

🔗 https://haroldco45.github.io/simulacro-nacional/

## Qué hace

- **Cuenta regresiva en hora Colombia** a las dos jornadas; muestra "en curso" y "jornada cumplida".
- **Mi plan**: hogar, empresa, colegio o comunidad; escenario (sismo, inundación, incendio, deslizamiento, vendaval); punto de encuentro, ruta, responsables y contactos. Recomendaciones según el escenario elegido.
- **Simulacro en vivo**: alarma con sonido y vibración, cronómetro y fases guiadas según el escenario; registra el tiempo de cada fase.
- **Lista de chequeo**: antes, durante, después y kit de emergencia de 72 horas, con barra de progreso.
- **Acta**: informe con tiempos, participantes, novedades y calificación, listo para WhatsApp, copiar o respaldar en .json.
- **Info**: líneas de emergencia (123, 119, 132, 144, UNGRD), marco oficial y fuentes.

## Privacidad

Todos los datos se guardan únicamente en el dispositivo del usuario (`localStorage`). No hay servidor ni envío de información. Aviso conforme a la Ley 1581 de 2012.

## Archivos

| Archivo | Función |
|---|---|
| `index.html` | App completa (HTML + CSS + JS) |
| `manifest.json` | Manifiesto PWA |
| `sw.js` | Service worker (funciona sin internet) |
| `icon-192.png`, `icon-512.png` | Íconos |
| `og.png` | Imagen 1200×630 para WhatsApp y redes |

## Publicación

GitHub Pages desde la rama `main`, carpeta raíz. Si cambia el nombre del repo, actualizar las URLs absolutas de `og:url`, `og:image`, `twitter:image` y el enlace del acta en `index.html`.

## Fuentes

- UNGRD — [fecha oficial del Simulacro 2026](https://portal.gestiondelriesgo.gov.co/Paginas/Noticias/2026/Atencion-Colombia-UNGRD-definio-la-fecha-para-el-Simulacro-Nacional-de-Respuesta-a-Emergencias-2026.aspx)
- [Circular 079 de 2026](https://safetya.co/normatividad/circular-079-de-2026/)
- [Semana — horarios y recomendaciones](https://www.semana.com/nacion/articulo/colombia-se-alista-para-el-simulacro-nacional-de-emergencias-horarios-y-recomendaciones/202605/)
- [International Charter — sismo del 10 de agosto de 2026](https://disasterscharter.org/es/activations/earthquake-in-colombia-activation-1048-)

---
**Desarrollada por Vibras Positivas HM — Derechos de Autor Reservados**
