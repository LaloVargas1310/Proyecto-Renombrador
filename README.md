# Proyecto-Renombrador (NexaDoc MVP)

Plataforma web inteligente (SaaS / On-Premise) diseñada para la automatización y optimización de la gestión documental en entornos administrativos y de oficina. 

El sistema resuelve el problema del caos de archivos sin clasificar mediante la lectura automatizada de documentos (PDFs), la extracción de texto clave a través de expresiones regulares (Regex) y una interfaz de validación para el usuario, permitiendo renombrar y organizar archivos de forma masiva y segura.

## 🚀 Características Principales (MVP)

* **Extracción de Texto:** Lectura precisa de archivos PDF ignorando elementos visuales innecesarios.
* **Análisis Inteligente (Parsing):** Motor basado en Regex para identificar automáticamente nombres de clientes, titulares, fechas o identificadores dentro del documento.
* **Filtro Humano (Validación):** Interfaz web limpia que permite al usuario confirmar, corregir o elegir entre múltiples nombres detectados antes de aplicar los cambios en el sistema de archivos.
* **Estructuración Personalizada:** Opción para prefijar o sufijar datos adicionales al nombre final del archivo (ej. fechas, departamentos, estados).
* **Arquitectura Multiplataforma:** Solución basada en entorno web, accesible desde cualquier sistema operativo sin necesidad de instalaciones locales complejas.

## 🛠️ Stack Tecnológico

* **Backend:** Python 3.x
* **Framework Web:** Django (robusto, seguro y escalable)
* **Procesamiento de Texto:** `pdfplumber` y módulo nativo `re` (Regular Expressions)
* **Base de Datos:** SQL (SQLite en desarrollo / PostgreSQL para producción)
* **Frontend:** HTML5, CSS3 (Tailwind CSS) y JavaScript básico

## 📦 Instalación y Configuración Local
PENDIENTE
   
