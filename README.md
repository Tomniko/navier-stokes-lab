# Laboratorio de Navier–Stokes

Web educativa interactiva para entender las ecuaciones de Navier–Stokes:
un **solver de fluido incompresible real corriendo en la GPU** (método de
proyección de presión / "stable fluids"), con vista **3D** del líquido y vista
**2D** del campo de velocidad, conectadas al mismo solver.

Cada control está mapeado a su término de la ecuación
(advección, presión, viscosidad, fuerza externa, incompresibilidad) y hay
presets de fluidos (agua, miel, aire/humo, aceite, glicerina).

## Uso
- **Arrastra sobre el panel 2D** (derecha) para inyectar fluido y fuerza.
- **Clic** = chasquido radial.
- **Arrastra sobre la vista 3D** (izquierda) para rotarla.

Todo corre en el navegador con WebGL2 + Three.js (vía CDN). No requiere servidor.

## Desarrollo local
Cualquier servidor estático sirve, p. ej.:

```bash
python3 -m http.server 8000
# luego abre http://localhost:8000/
```

## Publicado en
GitHub Pages → [https://tomniko.github.io/navier-stokes-lab/](https://tomniko.github.io/navier-stokes-lab/)
