# Arquitectura de la solución – Casanova App

## 🧠 Enfoque

La arquitectura de Casanova fue diseñada bajo tres principios:

- rapidez de desarrollo  
- escalabilidad  
- integración nativa de inteligencia artificial  

El objetivo no es complejidad técnica, sino **velocidad para validar valor real**.

---

## ⚙️ Componentes principales

### 1. Frontend

- Aplicación web responsiva (celular, tablet, desktop)
- Framework: Next.js
- Estilos: TailwindCSS

Responsabilidad:
- interacción con el usuario
- captura de información del proyecto
- visualización de resultados (renders, cotizaciones)

---

### 2. Backend

- Servicios en la nube (Firebase / serverless)
- API para gestión de usuarios, proyectos y datos

Responsabilidad:
- autenticación
- almacenamiento
- lógica de negocio
- integración con servicios externos

---

### 3. Motor de IA

- Generación de imágenes (renders) usando modelos como:
  - Stable Diffusion / DALL·E
- Asistente basado en OpenAI API

Responsabilidad:
- generación de propuestas visuales
- apoyo en descripción de proyectos
- estimación de costos preliminares

---

### 4. Integraciones externas

- WhatsApp Cloud API → notificaciones y contacto con proveedores  
- Nodemailer → envío de correos  
- almacenamiento en la nube  

Responsabilidad:
- comunicación automatizada
- activación del proceso comercial

---

## 🔄 Flujo de arquitectura

1. Usuario ingresa información en frontend  
2. Backend procesa y almacena datos  
3. Se activa el motor de IA  
4. IA genera renders y estimaciones  
5. Resultados se envían al frontend  
6. Usuario selecciona opción  
7. Sistema activa contacto con proveedores  
8. Notificaciones se envían por correo y WhatsApp  

---

## 🧩 Capacidades clave

- Generación automática de propuestas  
- Cotización estructurada  
- Gestión de proyectos  
- Comunicación automatizada  
- Escalabilidad en la nube  

---

## 📌 Diagrama de arquitectura

https://github.com/CESARAAH/fengshui-ai-remodel/blob/main/ai/Architecture_Diagram.mmd

---

## 🚀 Enfoque técnico

La arquitectura prioriza:

👉 rapidez de iteración sobre complejidad  
👉 validación de producto sobre perfección técnica  
👉 integración de IA en el flujo real del usuario  

---

## ⚠️ Principio clave

No se diseñó una arquitectura para escalar desde el día uno.

👉 Se diseñó una arquitectura para aprender rápido qué funciona y escalar después.
