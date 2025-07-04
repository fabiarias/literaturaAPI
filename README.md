# literaturaAPI
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

Aplicación de consola desarrollada en **Java + Spring Boot**, que consume la API pública de **[Gutendex](https://gutendex.com/)** para consultar libros gratuitos del Proyecto Gutenberg. La información seleccionada por el usuario se guarda en una base de datos **PostgreSQL**.

---

## 🚀 Características

- 🔌 Conexión a la API de Gutendex.
- 📖 Consulta de libros mediante un menú en consola.
- 🗃️ Almacenamiento de libros seleccionados en PostgreSQL.
- 📦 Arquitectura basada en Spring Boot (MVC, Repository, Service).
- ✅ Validaciones básicas y manejo de errores.

---

## 🛠️ Tecnologías utilizadas

- ![Java](https://img.shields.io/badge/Java-17+-orange?logo=java)
- ![Spring Boot](https://img.shields.io/badge/Spring--Boot-3.x-success?logo=spring)
- ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14+-blue?logo=postgresql)
- ![Maven](https://img.shields.io/badge/Maven-C71A36?logo=apache-maven&logoColor=white)

---

## 📦 Instalación y ejecución

### 🔧 Requisitos previos

- Java 17+
- Maven
- PostgreSQL (configurado y corriendo)
- IDE como IntelliJ IDEA o Eclipse (opcional)

### 🚀 Pasos para clonar y ejecutar

```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/gutendex-console-app.git
cd gutendex-console-app

# Configurar la conexión a la base de datos en application.properties
# Ejecutar la aplicación
mvn spring-boot:run
