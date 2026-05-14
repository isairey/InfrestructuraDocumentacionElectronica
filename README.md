<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/3135/3135692.png" />

# 🇲🇽 InSiDE MX

### Infraestructura y Sistema de Documentación Electrónica 🚀

<p align="center">
  <b>InSiDE MX</b> es una plataforma de administración documental electrónica enfocada en expedientes digitales, firmas electrónicas y gestión documental empresarial compatible con arquitecturas gubernamentales y corporativas modernas.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-Enterprise-orange?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/Maven-Build-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white">
  <img src="https://img.shields.io/badge/Documentación-Electrónica-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/WS-SOAP-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-roadmap">Roadmap</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**InSiDE MX** es un sistema de infraestructura documental diseñado para gestionar expedientes electrónicos, documentos digitales y servicios de firma electrónica dentro de entornos empresariales y gubernamentales.

La plataforma permite:

- 📂 Gestión de expedientes electrónicos
- 📄 Administración documental
- ✍️ Firmas digitales
- 🔐 Seguridad documental
- 🌐 Servicios web SOAP
- 📊 Integración empresarial
- 🗄️ Gestión de bases de datos
- ⚡ Automatización documental

El proyecto fue desarrollado para practicar:

- Java Enterprise
- Arquitectura SOA
- Servicios Web
- Gestión documental
- Integración de firmas electrónicas
- Administración de expedientes

---

# ✨ Características

## 📂 Gestión documental

- 📄 Administración de documentos
- 📁 Expedientes electrónicos
- 🔎 Búsqueda documental
- 📋 Metadatos avanzados
- 🗂️ Organización de expedientes

---

## ✍️ Firma electrónica

- 🔐 Firma digital en servidor
- 🖊️ Gestión de certificados
- 📑 Validación documental
- ⚡ Integración de firmas
- 🧾 Compatibilidad ENI

---

## 🌐 Servicios Web

- 📡 APIs SOAP
- 🔄 Integración empresarial
- 📂 Operaciones documentales
- 📋 Intercambio de expedientes
- ⚡ Servicios distribuidos

---

## 🔒 Seguridad

- 🔑 TrustStores JKS
- 🛡️ Configuración SSL
- 🔐 Gestión de credenciales
- 📄 Protección documental
- 👨‍💻 Control de accesos

---

# 🛠️ Tecnologías utilizadas

## ☕ Backend

<p>
  <img src="https://skillicons.dev/icons?i=java,maven" />
</p>

- Java 7+
- Maven
- WAR Deployment
- Servicios SOAP

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql,postgresql" />
</p>

- PostgreSQL
- MySQL
- SQL
- Scripts BBDD

---

## 🐳 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,docker,vscode" />
</p>

- Git
- GitHub
- Docker
- VS Code

---

# 📂 Estructura del proyecto

```bash
inside-mx/
│
├── fuentes/
│   ├── inside-web/
│   └── target/
│
├── resources/
│   ├── config/
│   └── scripts_bbdd/
│
├── deploy/
│
├── pom.xml
│
└── README.md
```

---

# ⚡ Instalación

## 📋 Requisitos

- Java 1.7 o superior
- Maven 3.3.9+
- PostgreSQL o MySQL
- Git
- Servidor de aplicaciones Java

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/carm-es/inside.git
```

---

## 2️⃣ Entrar al proyecto

```bash
cd inside
```

---

## 3️⃣ Compilar proyecto

```bash
mvn install
```

---

## 4️⃣ Archivo generado

La aplicación compilada se encontrará en:

```bash
fuentes/inside-web/target/inside.war
```

---

# ⚙️ Configuración

## 📂 Archivos de configuración

Ubicación:

```bash
/resources/config
```

---

## 🗄️ Scripts de base de datos

Ubicación:

```bash
/resources/scripts_bbdd
```

---

## 🔐 Variables importantes

Editar:

```properties
database.properties
```

Configurar:

```properties
url=
username=
password=
```

---

# 🖥️ VM Arguments

## ⚡ Configuración Java

```bash
-Dconfig.path="/path/to/resources/config/"
-DtmpShared.path="/path/to/temp/folder/"
-Dinside.hostDomainPort=localhost:8080
-Djavax.net.ssl.trustStore="/path/to/resources/config/trustStore.jks"
-Djavax.net.ssl.trustStorePassword="changeit"
```

---

# 🧩 Componentes Eeutils

## ⚡ Funcionalidades integradas

### ✍️ Eeutil-Firma

- Firma electrónica servidor
- Gestión de expedientes
- Firma documental

---

### 📄 Eeutil-Oper-Firma

- Información de firmas
- Validación documental
- Operaciones WS

---

### 👁️ Eeutil-Vis-Docexp

- Visualización PDF
- Expedientes digitales
- Documentos electrónicos

---

### 🛡️ Eeutil-Misc

- Validación ENI
- Servicios auxiliares
- Compatibilidad documental

---

### 🔑 Eeutil-Util-Firma

- Generación de credenciales
- Gestión de accesos
- Configuración de firmas

---

# 📸 Vista previa

<div align="center">

<img width="1000" src="https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?q=80&w=1200&auto=format&fit=crop" />

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Aprender y practicar

- Java Enterprise
- Arquitectura SOA
- SOAP Web Services
- Gestión documental
- Firmas electrónicas
- Expedientes digitales
- Integración empresarial

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- ☁️ Integración cloud
- 📱 Dashboard moderno
- 🤖 Automatización documental
- 🔒 Seguridad avanzada
- 📊 Analytics administrativos
- 📄 PDFs inteligentes
- ⚡ Microservicios

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Autor

<div align="center">

## InSiDE MX — Infraestructura documental empresarial

Sistema orientado a documentación electrónica, expedientes digitales y automatización empresarial moderna 🇲🇽

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto desarrollado para prácticas de documentación electrónica, integración empresarial y administración de expedientes digitales.

---

<div align="center">

### 🇲🇽 InSiDE MX — infraestructura moderna para documentación electrónica 🚀

</div>
