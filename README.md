# ✈️ Vuelo sobre Madrid

Simulador de vuelo en el navegador sobre la Comunidad de Madrid, con edificios 3D fotorrealistas (Google Photorealistic 3D Tiles vía CesiumJS).

**Juega aquí:** https://luisomorenoglez.github.io/vuelo-madrid/

## Modos

- **3D fotorrealista** — necesitas una clave gratuita: un token de [Cesium ion](https://ion.cesium.com/signup) (empieza por `eyJ...`) o una clave de Google Maps Platform con la Map Tiles API activada (`AIza...`). La clave se guarda solo en tu navegador.
- **Sin clave** — mapa plano de OpenStreetMap para probar los controles.

## Controles

| Tecla | Acción |
|---|---|
| `W`/`S` o `↑`/`↓` | Subir / bajar el morro |
| `A`/`D` o `←`/`→` | Girar |
| `Shift` / `Ctrl` | Acelerar / frenar |
| `1`–`5` | Viajar: Sol, Bernabéu, 4 Torres, Retiro, El Escorial |
| `Espacio` | Nivelar el avión |
| `Q` | Calidad gráfica (alta / media / rápida) |
| `C` | Vista cabina / exterior |
| `N` | Hora del día (mediodía / atardecer / noche / amanecer) |
| `R` | Volver al punto de inicio |

## Extras

- **Tres aeronaves**: avioneta, dron (ágil) y globo (turismo), cada una con su propia física.
- **Minimapa** en tiempo real (arriba a la derecha) con la ruta recorrida.
- **Estela luminosa** en 3D detrás de la aeronave.
- **Colisiones reales**: si chocas contra el suelo o un edificio, te estrellas y reapareces.
