# Tiro con Efecto ⚽🔥

Videojuego retro pixel art de tiros libres en HTML5 Canvas con simulación de efecto y física de curva. Dibuja la curva con el dedo o el ratón y el balón la seguirá según la velocidad y curvatura del trazo.

**[🎮 Jugar en vivo en Vercel](https://tiro-con-efecto.vercel.app)** · **[📦 Repositorio en GitHub](https://github.com/josmito93-debug/tiro-con-efecto)**

---

## 🎮 Cómo se juega

- **Disparar:** Haz clic o toca el balón, desliza hacia la portería y suelta donde quieras colocar el balón.
- **Efecto de rosca / curva:** Si dibujas un trazo curvado, el balón saldrá abierto y se cerrará en el aire emulando el efecto Magnus.
- **Fuerza y bombeo:**
  - Desliza rápido para disparar con potencia.
  - Desliza lento para tiros bombeados que superen la barrera por arriba.

## ✨ Características

- **Intro cinemática interactiva (`gameintro.mp4`):** Secuencia de apertura retro con banda sonora, control de audio y opción para saltar o repetir en cualquier momento.
- **Gráficos retro pixel art:** Perspectiva pseudo-3D inspirada en arcades clásicos de fútbol.
- **Física de efecto Magnus:** Simulación de rotación y trayectoria del balón en tiempo real.
- **IA de portero y barrera:** Saltos sincronizados de la barrera y estiradas defensivas del arquero.
- **HUD dinámico:** Puntuación, nivel de tiro, distancia al arco, balones restantes y barras de fuerza/efecto.
- **Lectura técnica de cada disparo:**
  - Velocidad
  - Giro del balón
  - Desvío por efecto
  - Tiempo de vuelo
- **Ajustes de prototipo en tiempo real:**
  - Regulador de fuerza del efecto (0% a 200%)
  - Estela de fuego
  - Cámara lenta al pasar la barrera
  - Giro suave del balón
  - Efectos de sonido con Web Audio API

## 🚀 Despliegue en Vercel

El proyecto está configurado como una aplicación estática ligera sin dependencias de compilación requeridas, alojado y desplegado de forma continua en Vercel.

- **URL de Producción:** [https://tiro-con-efecto.vercel.app](https://tiro-con-efecto.vercel.app)

```bash
# Probar localmente
npx serve .
```

## 📄 Licencia

MIT
