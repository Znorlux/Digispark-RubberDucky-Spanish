# Digispark-RubberDucky-Spanish

Este repo te permite configurar un **Digispark ATtiny85** como un **Rubber Ducky** en sistemas con teclados en español. 🦆💀  

## 📥 Instalación de Digispark en Arduino IDE

1️⃣ **Abrir Arduino IDE**  
2️⃣ Ir a **Archivo** > **Preferencias**  
3️⃣ En **Gestor de URLs Adicionales de Tarjetas**, agregar esta URL: 

https://raw.githubusercontent.com/digistump/arduino-boards-index/master/package_digistump_index.json

4️⃣ Ir a **Herramientas** > **Placa** > **Gestor de Tarjetas**  
5️⃣ Buscar **Digistump AVR Boards** e instalarlo  
6️⃣ Seleccionar la placa:  
- **Herramientas** > **Placa** > **Digispark (Default - 16.5mhz)**  

---

## 📥 Instalación del soporte para teclado en español

Para que el Digispark funcione correctamente con teclados en español, debes descargar estos archivos:  

1️⃣ Clonar el siguiente repo o descargar los archivos:  

```bash
git clone https://github.com/Dasor/digispark-keyboard-layout-Spanish
```
2️⃣ Copiar los archivos `DigiKeyboard.h` y `scancode-ascii-table.h` dentro de tu carpeta de librerías de Arduino:  
- **Windows**: `C:\Users\TU_USUARIO\Documents\Arduino\libraries\DigiKeyboard`  
- **Linux/macOS**: `~/Arduino/libraries/DigiKeyboard`  

---

## 🎯 Uso y Payloads

Dentro de este repositorio encontrarás **scripts (payloads)** listos para usar con Digispark. Solo carga el `.ino` en Arduino IDE, compila y ¡conéctalo a una PC para probarlo! 💣💻  

📌 **Ejemplos de payloads incluidos**:  
- **Reverse Shell instantanea**  
- **Simular escritura automática**  
- **Descargar y ejecutar archivos desde internet**  

---

## 🛠️ Contribuciones y mejoras

Este es un proyecto en crecimiento. Si tienes mejoras, nuevos payloads o ideas, ¡haz un **pull request** o abre un **issue**! 🚀  

🔗 Repo oficial: [Digispark Rubber Ducky Spanish](https://github.com/Znorlux/Digispark-RubberDucky-Spanish)  
