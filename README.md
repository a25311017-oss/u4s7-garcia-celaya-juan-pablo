# 🔐 Aplicación Web con Django | Unidad 4 - Semana 7

## 📌 Descripción del proyecto

Este proyecto forma parte de las actividades de la asignatura de **Desarrollo de Aplicaciones Web** de la Universidad Tecnológica de Hermosillo (UTH).

Consiste en una aplicación web desarrollada con Django que permite gestionar usuarios, controlar el acceso al sistema y administrar información de manera segura mediante una interfaz web.

**Unidad:** 4  
**Semana:** 7  
**Alumno:** Juan Pablo García Celaya  
**Matrícula:** 25311017  
**Grupo:** DSM 4-1

---

## 🚀 Características principales

- 🔑 **Autenticación de usuarios**
  - Registro de nuevos usuarios.
  - Inicio y cierre de sesión.
  - Manejo seguro de contraseñas mediante Django.

- 🛡️ **Control de acceso**
  - Protección de páginas que requieren autenticación.
  - Restricción de acceso a usuarios no autorizados.
  - Validación de sesiones.

- 📋 **Gestión de información**
  - Registro y consulta de información desde la aplicación.
  - Organización de los datos mediante modelos de Django.
  - Conexión con una base de datos.

- 💬 **Mensajes del sistema**
  - Notificaciones de éxito.
  - Avisos de errores.
  - Mensajes para orientar al usuario durante la navegación.

- 🎨 **Interfaz web**
  - Plantillas HTML.
  - Diseño adaptable con Tailwind CSS.
  - Navegación entre las diferentes secciones.

---

## 🛠️ Tecnologías utilizadas

- **Lenguaje:** Python 3.x
- **Framework web:** Django 5.x
- **Frontend:** HTML5, CSS3 y Tailwind CSS
- **Base de datos:** MySQL o SQLite, según la configuración del proyecto
- **Control de versiones:** Git y GitHub
- **Editor recomendado:** Visual Studio Code

---

## 📂 Estructura del proyecto

La estructura puede variar dependiendo de los archivos incluidos en la práctica.

```text
u4s7-garcia-celaya-juan-pablo/
│
├── manage.py
├── requirements.txt
├── README.md
│
├── miproyecto/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
└── core/
    ├── models.py
    ├── views.py
    ├── urls.py
    ├── forms.py
    └── templates/
```

---

## ⚙️ Instalación y configuración local

### 1. Clonar el repositorio

```bash
git clone https://github.com/a25311017-oss/u4s7-garcia-celaya-juan-pablo.git
```

### 2. Entrar a la carpeta del proyecto

```bash
cd u4s7-garcia-celaya-juan-pablo
```

### 3. Crear un entorno virtual

En Windows:

```powershell
python -m venv venv
```

### 4. Activar el entorno virtual

```powershell
.\venv\Scripts\Activate.ps1
```

### 5. Instalar las dependencias

```bash
pip install -r requirements.txt
```

### 6. Aplicar las migraciones

```bash
python manage.py migrate
```

### 7. Crear un superusuario (opcional)

```bash
python manage.py createsuperuser
```

### 8. Ejecutar el servidor de desarrollo

```bash
python manage.py runserver
```

Abrir la siguiente dirección en el navegador:

http://127.0.0.1:8000/

---

## 🔒 Consideraciones de seguridad

- No publicar contraseñas ni credenciales de bases de datos.
- Mantener `DEBUG = False` en producción.
- Configurar correctamente `ALLOWED_HOSTS`.
- Utilizar variables de entorno para los datos sensibles.
- Proteger las vistas y los formularios que requieren autenticación.
- Mantener actualizadas las dependencias del proyecto.

---

## 🎯 Objetivo de la práctica

Aplicar los conocimientos adquiridos durante la Unidad 4, Semana 7, mediante el desarrollo y la configuración de una aplicación web utilizando Django, reforzando el uso de modelos, vistas, plantillas, rutas y mecanismos de seguridad.

---

## 👨‍💻 Autor

**Juan Pablo García Celaya**  
Matrícula: 25311017  
Grupo: DSM 4-1  
Universidad Tecnológica de Hermosillo (UTH)

---

*Proyecto académico desarrollado con fines educativos.*
