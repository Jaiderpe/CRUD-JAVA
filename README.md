# CRUD-JAVA

# Proyecto de Gestión de Equipos de Fútbol

Este proyecto en **Java** permite gestionar equipos de fútbol, almacenando información sobre los equipos y sus jugadores.

## 📁 Estructura del Proyecto
```
futbol-proyecto/
├── src/
│   ├── models/
│   │   ├── Equipo.java        // Clase Equipo
│   │   ├── Jugador.java       // Clase Jugador
│   ├── services/
│   │   ├── EquipoService.java // Servicio para gestionar equipos
│   ├── main/
│   │   ├── Main.java          // Punto de entrada del programa
│── resources/
│   ├── equipos.json           // (Opcional) Archivo para almacenar equipos
│── tests/
│   ├── EquipoTest.java        // Pruebas unitarias
│   ├── JugadorTest.java       // Pruebas unitarias
│── README.md
│── pom.xml (si usas Maven) o build.gradle (si usas Gradle)
```

## 🚀 Tecnologías Utilizadas
- **Java 11+**
- **Maven o Gradle** (opcional para gestión de dependencias)

## ⚙️ Instalación y Uso
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/futbol-proyecto.git
   ```
2. Navegar al directorio del proyecto:
   ```bash
   cd futbol-proyecto
   ```
3. Compilar y ejecutar el proyecto:
   ```bash
   javac -d bin src/main/Main.java
   java -cp bin main.Main
   ```
   O si usas Maven:
   ```bash
   mvn compile exec:java
   ```

## 📌 Funcionalidades
✅ Registrar equipos con nombre, ciudad, fecha de fundación y presidente.  
✅ Agregar jugadores a un equipo con número de dorsal, nombre, ciudad y edad.  
✅ Listar todos los equipos registrados.  

## 📜 Licencia
Este proyecto está bajo la licencia **MIT**.

---
👨‍💻 Desarrollado por [Jaider Adrian Perez Vega]

