# CertUAE

## 📌 Descripción
**CertUAE** es un software en construcción desarrollado en **.NET 8** cuyo objetivo es **analizar unidades de almacenamiento y directorios**, extraer **metadatos estructurales y de contenido** desde diferentes tipos de archivos (PDF, TIFF, Excel, bases de datos, entre otros) y **generar reportes técnicos** que apoyan procesos de **certificación, auditoría y digitalización documental**.

El proyecto está diseñado bajo una arquitectura modular basada en **servicios**, lo que permite su extensión y adaptación a diferentes contextos institucionales o empresariales.

---

## 🎯 Objetivos del Software

- Escanear directorios y unidades de almacenamiento externas (UAE)
- Identificar estructura de carpetas y archivos
- Extraer metadatos técnicos (nombre, tamaño, fechas, formato, hash)
- Analizar archivos PDF, TIFF y Excel
- Validar reglas estructurales definidas
- Generar reportes en formato **CSV / TXT**
- Conectarse a bases de datos y generar **diccionarios de datos**

---

## 🧩 Funcionalidades Principales

- 📁 Escaneo de carpetas y subcarpetas
- 🧾 Análisis de archivos PDF (metadatos y validación)
- 🖼️ Procesamiento de imágenes TIFF
- 📊 Lectura de archivos XLS / XLSX
- 🔐 Generación de hash (integridad de archivos)
- 🗄️ Conexión a bases de datos MySQL
- 📚 Generación automática de diccionarios de datos
- 📑 Exportación de resultados a archivos CSV

---

## 🏗️ Arquitectura

El proyecto utiliza:

- .NET 8
- Inyección de dependencias (`Microsoft.Extensions.DependencyInjection`)
- Entity Framework Core
- Arquitectura por capas:
  - `Services`
  - `Models`
  - `Utilities`
  - `DbContext`

---

## ⚙️ Requisitos del Sistema

- Sistema Operativo: **Windows 10 / 11**
- .NET SDK **8.0 o superior**
- Acceso a consola (CMD / PowerShell)
- (Opcional) Base de datos MySQL

---

## ▶️ Ejecución del Proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/tu-usuario/CertUAE.git
```

2. Acceder al directorio del proyecto:

```bash
cd CertUAE
```

3. Restaurar dependencias:

```bash
dotnet restore
```

4. Ejecutar la aplicación:

```bash
dotnet run
```

---

## 🧪 Estado del Proyecto

🚧 **En desarrollo activo**

- Algunas funcionalidades pueden cambiar
- La estructura está sujeta a mejoras
- Se recomienda usar en entornos de prueba

---

## 📄 Licenciamiento

### Opción 1: GNU GPL v3 (Software Libre)

Recomendada si deseas:
- Mantener el código abierto
- Obligar a que las modificaciones también sean abiertas
- Evitar que terceros vendan el software sin liberar cambios

### Opción 2: GNU LGPL v3

Recomendada si:
- Deseas permitir el uso del software como librería en proyectos privados
- Mantener el núcleo abierto

### Opción 3: Licenciamiento Dual (Recomendado 💼)

Permite:
- Publicar el proyecto bajo **GPL**
- Ofrecer una **licencia comercial** para:
  - Uso cerrado
  - Integración empresarial
  - Soporte técnico

> ✔️ Esta modalidad te permite **cobrar por uso, soporte o personalización**.

---

## 💼 Licencia Comercial (Propuesta)

Puedes ofrecer:

- Uso comercial sin obligación de liberar código
- Soporte técnico
- Adaptaciones a medida
- Certificación institucional

Ejemplo de texto:

> "CertUAE está disponible bajo licencia GPL v3 para uso libre. Para uso comercial, institucional o cerrado, se requiere una licencia comercial otorgada por el autor."

---

## 👨‍💻 Autor

**Jhonatan Moreno**  
Desarrollador Fullstack & Arquitecto de Software  

---

## 📬 Contacto

Para licencias comerciales, soporte o contribuciones:

📧 Email: contacto@tudominio.com

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas bajo la licencia seleccionada.

1. Fork del proyecto
2. Crear rama (`feature/nueva-funcionalidad`)
3. Commit de cambios
4. Pull Request

---

## 🛡️ Aviso Legal

Este software se proporciona "TAL CUAL", sin garantías explícitas o implícitas. El autor no se hace responsable del uso indebido del software.

