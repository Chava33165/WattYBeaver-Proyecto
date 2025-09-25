# ⚡ Watt&Beaver: El Guardián de tu Hogar

¡Bienvenido a **Watt&Beaver**, un proyecto de **código abierto** diseñado para ayudarte a tomar el control de tu consumo de **energía** y **agua** en el hogar!  
En un mundo donde el desconocimiento sobre nuestros hábitos de consumo se traduce en gastos innecesarios y desperdicio de recursos, nuestra misión es **empoderarte con información en tiempo real** y herramientas inteligentes para ahorrar dinero y proteger el planeta.

Este proyecto de titulación se basa en la integración de **hardware de bajo costo (IoT)** con un **software robusto** y una **aplicación móvil intuitiva** para crear un sistema integral de monitoreo y gestión.

---

## 🎯 El Problema y Nuestra Solución

En muchos hogares, el consumo de electricidad y agua es un misterio.  
Las facturas llegan, pero no sabemos qué electrodoméstico consume más o cuánta agua usamos al bañarnos.  
Esto impide tomar decisiones informadas para ser más eficientes.

**Watt&Beaver ofrece una solución integral:**

- 🔌 **Monitoreo en tiempo real:** Visualiza instantáneamente tu consumo de energía y agua.  
- 💡 **Ahorro inteligente:** Recibe estimaciones de costos y consejos personalizados para reducir tus gastos.  
- 🌍 **Conciencia ambiental:** Promueve el uso responsable de recursos, contribuyendo a los **ODS de la ONU**.  
- 🎮 **Gamificación:** Transforma el ahorro en un juego con retos y recompensas virtuales.  

---

## ⚙️ Arquitectura del Sistema

La magia detrás de Watt&Beaver reside en su arquitectura, que combina hardware y software de manera eficiente:

### 🔧 Hardware
- **Dispositivos de Medición:**  
  - Enchufes inteligentes **Sonoff S31/S26** con firmware **Tasmota/ESPHome** para consumo eléctrico.  
  - Sensores de flujo de agua **YF-S201** conectados a **ESP32/ESP8266**.  
- **Servidor Central:**  
  Una **Raspberry Pi** recopila y procesa todos los datos.  

### 💻 Software
- **Backend:** Node.js + Express para la lógica y la API REST.  
- **Comunicación:** Broker **MQTT (Mosquitto)** para mensajes ligeros y rápidos.  
- **Base de Datos:** MySQL/PostgreSQL para análisis y almacenamiento.  
- **Frontend:** App móvil multiplataforma con **React Native**.  

---

## ✨ Características Principales

- 📈 **Dashboard intuitivo:** Gráficas de consumo por hora, día, semana y mes.  
- 💲 **Estimación de costos:** Calcula el gasto aproximado en tu moneda local.  
- 🎮 **Gamificación:** Retos semanales y recompensas virtuales.  
- 📱 **Control remoto:** Enciende o apaga enchufes inteligentes desde la app.  
- 🔄 **Escalable:** Fácil de ampliar con más dispositivos o funciones.  

---

## 🛠️ Herramientas y Tecnologías

| Categoría      | Herramientas/Tecnologías |
|----------------|--------------------------|
| **Hardware**   | Raspberry Pi, ESP32, Sonoff S31/S26, Sensor YF-S201 |
| **Backend**    | Node.js, Express, Mosquitto (MQTT), MySQL/PostgreSQL |
| **Frontend**   | React Native, react-native-chart-kit |
| **Flujo**      | Git, GitHub, Docker, Trello/Notion |

---

## 🚀 Plan de Trabajo (Roadmap – 6 Meses)

- **Mes 1:** Configuración de Raspberry Pi, investigación y arquitectura inicial.  
- **Mes 2:** Configuración de dispositivos Sonoff y diseño de base de datos.  
- **Mes 3:** Desarrollo del backend (API REST y lógica).  
- **Mes 4:** Desarrollo de la app móvil (UI/UX + conexión al backend).  
- **Mes 5:** Integración de sensores de agua y módulo hídrico en la app.  
- **Mes 6:** Gamificación, pruebas finales y documentación.  

---

## 👨‍💻 Autores  

- Salvador Antonio Pantoja Vera  
- Edgar Gael Álvarez González  

---

© 2024 **Watt&Beaver**. Todos los derechos reservados.
