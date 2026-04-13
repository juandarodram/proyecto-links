# 🚀 Implementación de Aplicación Web en AWS con Docker y CI/CD

## 📌 Descripción
Este proyecto consiste en el despliegue de una aplicación web en un entorno cloud utilizando **AWS EC2** y **Docker**, garantizando portabilidad y consistencia del sistema.

Se aplicaron prácticas de **DevOps**, incluyendo control de versiones con GitHub y automatización del despliegue mediante un pipeline básico de **CI/CD**.

---

## ⚙️ Tecnologías utilizadas
- Docker  
- AWS EC2  
- GitHub  
- GitHub Actions (CI/CD)  
- Linux  

---

## 🧱 Arquitectura
Cliente → Servidor EC2 → Contenedor Docker → Aplicación Web

---

## 🚀 Despliegue

### 1. Clonar repositorio
```bash
git clone https://github.com/juandarodram/proyecto-links.git
cd proyecto-links
```

### 2. Construir imagen Docker
```bash
docker build -t mi-sitio .
```

### 3. Ejecutar contenedor
```bash
docker run -d -p 3000:80 --restart always mi-sitio
```

### 🌐 Demo
👉 [Ver aplicación desplegada](http://54.224.212.18:3000/)

🔄 CI/CD

Se implementó un pipeline básico utilizando GitHub Actions para automatizar procesos de integración y despliegue del proyecto.

🧠 Aprendizajes
Despliegue de aplicaciones en AWS EC2
Uso de contenedores con Docker
Configuración de puertos y redes
Resolución de problemas de conectividad (HTTP vs HTTPS)
Implementación de CI/CD básico
