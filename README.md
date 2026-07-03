# 🛩️ 1942: El Clásico de Capcom

Bienvenidos al resumen definitivo de **1942**, el juego que definió los cimientos de los shooters de scroll vertical. Lanzado por Capcom en 1984, este título nos transporta a las batallas aéreas más intensas del Pacífico. 

---

## 📊 Ficha Técnica

| Categoría | Detalle |
| :--- | :--- |
| **Desarrollador** | Capcom |
| **Diseñador** | Yoshiki Okamoto |
| **Lanzamiento** | 1984 |
| **Género** | Shoot 'em up (V-Scrolling) |
| **Niveles** | 32 Etapas |
| **Protagonista** | Lockheed P-38 Lightning |

---

## 🎮 Controles y Comandos ("Lo que mandan")

Si te preguntas qué se necesita para pilotar esta leyenda, aquí tienes los comandos básicos del gabinete original:

*   **Palanca (Joystick)**: Controla el movimiento en 8 direcciones por toda la pantalla.
*   **Botón 1 (Fuego)**: Disparo estándar. ¡Mantén el ritmo para no ser derribado!
*   **Botón 2 (Rizo/Loop)**: Realiza un giro de 360° en el aire. Te vuelve **invulnerable** temporalmente. Úsalo con sabiduría, ¡es limitado!

---

## 🚀 Mecánicas Principales

### 🔴 Los Aviones Rojos y el "POW"
Cuando eliminas una formación completa de aviones enemigos rojos, aparecerá un ícono de **POW**. Capturarlo es clave para tu supervivencia:

1.  **Escoltas**: Dos mini-aviones que vuelan a tus lados, duplicando tu potencia de fuego.
2.  **Munición Triple**: Mejora tu disparo simple a uno más ancho.
3.  **Destrucción Total**: Limpia todos los enemigos en pantalla instantáneamente.

### 🗺️ El Camino a Tokio
El juego utiliza un sistema de niveles regresivo, comenzando en el nivel 32 (Midway) y terminando en el nivel 1 (Tokio).

```mermaid
graph TD
    A[Nivel 32: Midway] --> B[Nivel 24: Islas Marshall]
    B --> C[Nivel 16: Islas Salomón]
    C --> D[Nivel 8: Iwo Jima]
    D --> E[Nivel 1: TOKIO]
    style E fill:#f96,stroke:#333,stroke-width:4px
```

---

## 🌟 Curiosidades y Legado

> [!IMPORTANT]
> **1942** fue el primer juego de Capcom en ser portado a una consola casera (la NES), lo que ayudó a cimentar la fama mundial de la compañía.


*   **Puntuación por Derribos**: Al final de cada nivel, se te evalúa con un porcentaje. Si no alcanzas un mínimo, ¡perderás jugosas bonificaciones!
*   **Música de Marcha**: La banda sonora utiliza un efecto de "tam-tam" militar que es reconocido instantáneamente por cualquier veterano de los arcades.


---

## 🖼️ Galería de Sprites

A continuación se muestran los sprites y assets disponibles para el proyecto, extraídos de las hojas de referencia oficiales de *1942*.

### Avión del Jugador — Lockheed P-38 Lightning

| Frame 1 | Frame 2 | Frame 3 | Frame 4 |
|:-------:|:-------:|:-------:|:-------:|
| <img src="player_plane_1.png" width="48"><br>Avión centro | <img src="player_plane_2.png" width="48"><br>Avión centro 2 | <img src="player_plane_3.png" width="48"><br>Avión centro 3 | <img src="player_plane_4.png" width="48"><br>Avión centro 4 |

| Inclinado izquierda | Inclinado derecha | Rizo (loop) | Despegue / Aterrizaje |
|:-------------------:|:-----------------:|:-----------:|:---------------------:|
| <img src="player_plane_left.png" width="48"><br>Izquierda | <img src="player_plane_right.png" width="48"><br>Derecha | <img src="player_roll_1.png" width="48"><br>Roll | <img src="player_takeoff_1.png" width="48"><br>Despegue |

| Explosión del jugador |
|:---------------------:|
| <img src="player_explosion_1.png" width="48"><br>Explosión |

### Escolta y Proyectiles

| Avión escolta | Bala del jugador |
|:-------------:|:----------------:|
| <img src="player_escort_flying.png" width="48"><br>Escolta | <img src="player_bullet.png" width="24"><br>Bala |

### Enemigos

| Tipo 1 | Tipo 2 | Tipo 3 | Tipo 4 |
|:------:|:------:|:------:|:------:|
| <img src="enemy_plane_1.png" width="48"><br>Enemigo 1 | <img src="enemy_plane_2.png" width="48"><br>Enemigo 2 | <img src="enemy_plane_3.png" width="48"><br>Enemigo 3 | <img src="enemy_plane_4.png" width="48"><br>Enemigo 4 |

| Kurogane Kai | Akotzu | Bud | Shoryu |
|:------------:|:------:|:---:|:------:|
| <img src="enemy_kurogane_kai.png" width="48"><br>Kurogane Kai | <img src="enemy_akotzu.png" width="48"><br>Akotzu | <img src="enemy_bud.png" width="48"><br>Bud | <img src="enemy_shoryu.png" width="48"><br>Shoryu |

| Raizan | Fukusuke / Yosuke | Qing | Daihiryu |
|:------:|:-----------------:|:----:|:--------:|
| <img src="enemy_raizan.png" width="48"><br>Raizan | <img src="enemy_fukusuke.png" width="48"><br>Fukusuke | <img src="enemy_qing.png" width="48"><br>Qing | <img src="enemy_daihiryu.png" width="80"><br>Daihiryu |

### Jefes y Power-ups

| Jefe Ayako | Explosión enemiga | Power-up POW |
|:----------:|:-----------------:|:------------:|
| <img src="boss_ayako.png" width="120"><br>Ayako | <img src="explosion_enemy_1.png" width="48"><br>Explosión enemiga | <img src="powerup_pow.png" width="48"><br>POW |


---

> [!TIP]
> No uses el "Rizo" (Loop) contra los jefes grandes (como el bombardero Ayako) a menos que sea estrictamente necesario para esquivar una bala, ya que es mejor posicionarse bien para seguir disparando.
