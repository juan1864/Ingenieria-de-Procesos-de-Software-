# 🏥 Sistema de Gestión Hospitalaria
### Proyecto académico — Ingeniería de Procesos de Software

Sistema web diseñado para optimizar y automatizar los procesos administrativos y clínicos dentro de una institución de salud, permitiendo la gestión integral de pacientes, médicos, citas médicas, historias clínicas y medicamentos.

Este proyecto fue desarrollado como parte de la asignatura **Ingeniería de Procesos de Software**, aplicando conceptos de análisis de requerimientos, diseño de software y buenas prácticas de desarrollo.

---

## 📌 Descripción del proyecto

El **Sistema de Gestión Hospitalaria** busca mejorar la eficiencia operativa de hospitales, clínicas y centros médicos mediante la digitalización de procesos clave, garantizando una administración centralizada, segura y confiable.

El sistema permite:

- Registrar y administrar pacientes.
- Gestionar información de médicos y especialidades.
- Programar, modificar y cancelar citas médicas.
- Consultar y actualizar historias clínicas.
- Administrar inventario de medicamentos.
- Generar reportes médicos y administrativos.
- Controlar acceso mediante autenticación de usuarios.

---

# 📂 Estructura del proyecto

```text
hospital_management_system/
├── app.py                    # Lógica principal del sistema
├── database.py               # Conexión y operaciones base de datos
├── models/
│   ├── patient.py            # Gestión de pacientes
│   ├── doctor.py             # Gestión de médicos
│   ├── appointment.py        # Gestión de citas
│   ├── medical_record.py     # Historias clínicas
│   └── medication.py         # Gestión de medicamentos
├── templates/
│   ├── login.html
│   ├── dashboard.html
│   ├── patients.html
│   ├── doctors.html
│   ├── appointments.html
│   └── reports.html
├── static/
│   ├── style.css
│   └── app.js
└── README.md


✅ Requerimientos Funcionales (RF)

Los requerimientos funcionales describen las funcionalidades que debe cumplir el sistema.

Código	Descripción
RF-01	Registrar pacientes
RF-02	Editar información de pacientes
RF-03	Eliminar pacientes
RF-04	Registrar médicos
RF-05	Asignar especialidades médicas
RF-06	Agendar citas médicas
RF-07	Cancelar citas
RF-08	Reprogramar citas
RF-09	Consultar disponibilidad médica
RF-10	Crear historias clínicas
RF-11	Actualizar historias clínicas
RF-12	Consultar antecedentes médicos
RF-13	Registrar medicamentos
RF-14	Actualizar inventario
RF-15	Alertar medicamentos agotados
RF-16	Generar reportes médicos
RF-17	Generar reportes administrativos
RF-18	Autenticación de usuarios
RF-19	Gestión de roles
RF-20	Enviar recordatorios de citas
🔒 Requerimientos No Funcionales (RNF)

Los requerimientos no funcionales describen los estándares de calidad del sistema.

Código	Descripción
RNF-01	Disponibilidad 24/7
RNF-02	Tiempo de respuesta menor a 2 segundos
RNF-03	Soportar mínimo 500 usuarios simultáneos
RNF-04	Cifrado de información médica
RNF-05	Autenticación segura
RNF-06	Copias de seguridad automáticas
RNF-07	Compatibilidad con navegadores modernos
RNF-08	Interfaz intuitiva y amigable
RNF-09	Integridad de los datos
RNF-10	Escalabilidad
RNF-11	Cumplimiento de privacidad de datos
RNF-12	Fácil mantenimiento
🛠️ Tecnologías utilizadas
Python
Flask
MySQL
HTML5
CSS3
JavaScript
Git y GitHub
🎯 Objetivo académico

Aplicar los conocimientos adquiridos en la materia Ingeniería de Procesos de Software, desarrollando un sistema real que permita:

análisis de requerimientos
diseño del sistema
modelado de procesos
documentación técnica
implementación de software
👨‍💻 Autor

Juan Diego Baquero Ovalle
Estudiante de Ingeniería de Software

📚 Materia

Ingeniería de Procesos de Software
