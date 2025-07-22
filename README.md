# 🏥 Sistema de Agendamiento de Citas Médicas

Este proyecto es un **sistema web para la gestión de citas médicas**, desarrollado con el objetivo de facilitar la interacción entre **administradores, especialistas y pacientes**. Permite a los pacientes agendar citas en línea, visualizar la disponibilidad de los especialistas y contactar soporte en caso de dudas.

## 🚀 Características principales

✅ **Gestión de usuarios con roles**  
- **Administrador**: administra usuarios, especialistas y especialidades.  
- **Especialista**: gestiona su disponibilidad y atiende las citas asignadas.  
- **Paciente**: agenda citas médicas, consulta disponibilidad y contacta soporte.

✅ **Agendamiento de citas**  
- Visualización de **especialidades médicas** con fotos y descripciones.  
- Selección de fecha y hora según **disponibilidad del especialista**.  
- Validación automática de horarios y duración de las citas.

✅ **Gestión de disponibilidad**  
- Los especialistas registran su disponibilidad de manera dinámica.  
- Los pacientes solo pueden agendar en horarios habilitados.

✅ **Soporte y ayuda**  
- Vista de **Preguntas Frecuentes (FAQ)**.  
- **Formulario de contacto** para pacientes.  
- Sección para guías, tutoriales e información de contacto.

✅ **Dashboard informativo**  
- Contenedor dinámico con especialidades y descripciones.  
- Integración opcional con **Google Maps** para ubicar la entidad médica.

---

## 🛠️ Tecnologías utilizadas

- **Backend**: PHP (arquitectura MVC)  
- **Base de datos**: MySQL  
- **Frontend**: HTML5, CSS3, JavaScript  
- **Framework CSS**: [Bulma](https://bulma.io/)  
- **Alertas**: SweetAlert2  
- **Control de versiones**: Git  

---

## 📌 Instalación y configuración

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
2. **Configurar la base de datos**:
   - Crear una base de datos en MySQL.  
   - Importar el archivo `BD_ProyectoSena.sql`.  
   - Configurar la conexión en el archivo correspondiente (por ejemplo, `config.php`).  

3. **Iniciar el servidor local** (XAMPP, WAMP o similar):
   - Colocar el proyecto en la carpeta `htdocs` (o la correspondiente).  
   - Ingresar desde el navegador:  
     ```
     http://localhost/proyectoSena2024/
     ```

---

## 👥 Roles y permisos

| Rol             | Funciones principales                                                                |
|------------------|---------------------------------------------------------------------------------------|
| **Administrador** | CRUD de usuarios, especialistas y especialidades. Gestión global del sistema.        |
| **Especialista**  | Visualiza su disponibilidad, atiende citas, actualiza datos personales.              |
| **Paciente**      | Agenda y cancela citas, consulta especialistas y servicios, contacta soporte.        |

---
## 📷 Capturas 

```markdown
![Vista de Registro](proyectoSena2024\app\views\fotos\vistaRegisto.png)
![Vista de Inicio de Sesión](proyectoSena2024\app\views\fotos\vistaIniciarSesion.png)
![Dashboard Usuario](proyectoSena2024\app\views\fotos\dashboardUsuario.png)
![Dashboard Administrador](proyectoSena2024\app\views\fotos\dashboardAdministrador.png)
![Dashboard Especialista](proyectoSena2024\app\views\fotos\dashboardEspecialista.png)
![Dashboard Paciente](proyectoSena2024\app\views\fotos\dashboardPaciente.png)
![Vista de lista de Usuarios y Datos Personales](proyectoSena2024\app\views\fotos\vistaListaUsuarioPersona.png)
![Vista de lista de Pacientes](proyectoSena2024\app\views\fotos\vistaPacientes.png)
![Vista de lista de Especialistas](proyectoSena2024\app\views\fotos\vistaEspecialista.png)
![Vista de lista de Especialidades](proyectoSena2024\app\views\fotos\vistaEspecialidad.png)
![Vista de Actualizar Perfil](proyectoSena2024\app\views\fotos\vistaActualizarPerfil.png)
![Vista de Especialistas por Especialidad](proyectoSena2024\app\views\fotos\vistaEspecialistasPorEspecialidad.png)
![Vista de Servicios Médicos y Agendar Citas - Paciente](proyectoSena2024\app\views\fotos\vistaServicioMedicos.png)
![Vista de Citas pendientes - Especialista](proyectoSena2024\app\views\fotos\vistaCitasEspecialista.png)
![Vista de Citas Agendadas - Paciente](proyectoSena2024\app\views\fotos\citasAgendadasPaciente.png)
![Vista de Citas pendientes - Especialista](proyectoSena2024\app\views\fotos\vistaCitasEspecialista.png)
```

---

## 📩 Contacto

Si tienes dudas o sugerencias, puedes comunicarte con nosotros a través de:  
- **Correo:** hguerreropalacios17@gmail.com  
- **Teléfono:** +57 304 595 5299  

---
