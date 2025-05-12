# 🚀 Galactica - Shooter Espacial en Python   

Un juego arcade estilo *shooter* espacial desarrollado con **Python** y **Pygame**, donde controlas una nave para destruir meteoros y sobrevivir el mayor tiempo posible.

---

## 📦 **Instalación**  

### Requisitos previos  
- Python 3.10+  
- Pygame 2.6+  

### Pasos para ejecutar el juego  
1. Clona el repositorio:  
   ```bash
   git clone https://github.com/Fabriciogg8/galactica.git
   cd galactica
   ```

2. Instala las dependencias:  
   ```bash
   pip install pygame
   ```

3. Ejecuta el juego:  
   ```bash
   python galactica.py
   ```

---

## 🎮 **Controles**  
- **← →**: Mover nave.  
- **ESPACIO**: Disparar.  
- **POWER-UPS**:  
  - **Escudo (⚡)**: Recupera salud.  
  - **Arma (🔫)**: Disparo doble temporal.  

---

## 🛠️ **Tecnologías y características**  
- **Motor gráfico**: Pygame (renderizado 2D, manejo de sprites y sonidos).  
- **POO**: Clases para jugador, enemigos, balas y explosiones.  
- **Sistemas**:  
  - Colisiones con detección por radio (`pygame.sprite.collide_circle`).  
  - Partículas para explosiones (animaciones sprite sheet).  
  - Música de fondo y efectos de sonido.  

---

## 📂 **Estructura del proyecto**  
```plaintext
galactica/
├── img/                  # Assets gráficos
│   ├── spaceShip_Fabricio.png
│   ├── meteorGrey_*.png
│   └── explosions/
├── snd/                  # Efectos de sonido y música
│   ├── Laser_Shoot.wav
│   └── dj_synth_wave.mp3
├── galactica.py          # Código principal
└── README.md
```

---

## ✨ **Créditos y licencias**  
- **Artistas**:  
  - Sprites: [Kenney.nl](https://kenney.nl/) (CC0 1.0 Universal).  
  - Música: [DJ Synth Wave](https://musiccompositionhacks.blogspot.com/) (licencia personalizada, ver enlace original).  
- **Desarrollador**: **Fabricio González** - ¡Conéctate en [LinkedIn](https://www.linkedin.com/in/fabriciogonzalezguasque/)]!  

---

## 🐛 **Reportar problemas**  
¿Encontraste un bug o tienes una sugerencia? Abre un [issue](https://github.com/Fabriciogg8/galactica/issues) en el repositorio.  

---

## 📄 **Licencia**  
Este proyecto está bajo **MIT License**. Ver [LICENSE](LICENSE) para más detalles.  

---

### 🔗 **Enlaces útiles**  
- [Documentación de Pygame](https://www.pygame.org/docs/)  
- [Más assets gratuitos para juegos](https://itch.io/game-assets/free)  

--- 

💡 **Nota**: Si el juego usa recursos con licencias restrictivas, asegúrate de reemplazarlos o añadir permisos explícitos.  

--- 

¿Te gustó el proyecto? ¡Déjale una ⭐ en el repositorio!
