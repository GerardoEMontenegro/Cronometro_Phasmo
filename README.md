⏱️ Cronómetro para Phasmophobia
Un cronómetro simple y funcional desarrollado en Python, ideal para usar durante partidas de Phasmophobia, donde controlar el tiempo es clave para planear estrategias y evitar la muerte 😱.

🎮 Funciones principales
El cronómetro se controla completamente con el teclado, permitiendo operar sin usar el mouse ni cambiar de ventana:

Tecla	Función
7	Iniciar cronómetro
8	Pausar cronómetro
9	Reiniciar (00:00)
0	Cerrar la aplicación

🖼️ Interfaz gráfica
Tamaño compacto: 300x100 px

Fondo trasnparente para evitar distracciones

Posición: esquina superior derecha de la pantalla

Texto grande y claro para rápida visualización



markdown
Copiar
Editar
![Cronómetro en funcionamiento](screenshot.png)
🛠️ Tecnologías utilizadas
Python 3

Tkinter: para la GUI

Keyboard: para escuchar teclas globalmente

🚀 Cómo usarlo
Clonar o descargar el repositorio

bash
Copiar
Editar
git clone https://github.com/tu_usuario/cronometro-phasmo.git
cd cronometro-phasmo
Instalar dependencias

bash
Copiar
Editar
pip install keyboard
Ejecutar el script

bash
Copiar
Editar
python cronometro.py
⚠️ En Windows, puede que necesites ejecutar como administrador para que el módulo keyboard funcione correctamente.

📁 Estructura del proyecto
bash
Copiar
Editar
cronometro-phasmo/
├── cronometro.py         # Script principal
├── screenshot.png         # (Opcional) Captura de pantalla del cronómetro
└── README.md              # Este archivo
💡 Mejoras posibles
Si querés seguir mejorándolo, acá van algunas ideas:

✅ Contador de segundos con décimas (formato MM:SS.ss)

🎨 Agregar botones en pantalla (como alternativa al teclado)

🔊 Agregar sonidos al iniciar/detener

🌙 Modo claro / oscuro

🎮 Integración con overlay en juegos usando pywin32 o OBS

📄 Licencia
MIT — Usalo, modificá y compartilo libremente ✌️