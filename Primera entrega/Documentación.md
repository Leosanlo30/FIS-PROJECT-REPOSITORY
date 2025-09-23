# 📌 Proyecto SOF – PeerHive

## 💡 Idea Principal  
Plataforma de **asesorías personalizadas entre pares**, diseñada para estudiantes de ingeniería de software.  

---

## ❗ Problemática  
Los alumnos de primeros semestres necesitan apoyo en materias específicas de la carrera. Sin embargo, enfrentan dificultades para recibir asesorías debido a:  

- Horarios complicados.  
- Traslados largos (estudiantes foráneos).  
- Carga académica y laboral que no permite acudir a sesiones presenciales.  

---

## 🛠️ Producto  
**PeerHive**: Plataforma web que conecta a estudiantes que necesitan asesorías con alumnos avanzados que buscan brindar apoyo y obtener créditos optativos.  

### 📖 Descripción del Producto  
- Facilita el contacto entre alumnos con necesidad de asesorías y asesores capacitados.  
- **Flexibilidad de horarios** para ambos perfiles.  
- **Soporte académico mutuo** con registro de horas y acreditación de créditos.  

---

## 👥 Usuarios  

### Primarios  
1. **Alumnos de primeros semestres (1º-4º):**  
   - No disponen de tiempo para asesorías presenciales.  
   - Estudiantes foráneos o en viajes.  
   - Necesitan reforzar conocimientos en materias específicas.  

2. **Alumnos con más de 180 créditos:**  
   - Buscan obtener créditos optativos.  
   - Trabajan o viven lejos de la facultad.  
   - Requieren horarios flexibles.  
   - Desean compartir su conocimiento con otros.  

### Secundarios / Potenciales  
- **Coordinador de LIS y administrativos:**  
  - Agilizan acreditación de optativas.  
  - Gestionan documentación y registro de horas.  

---

## 🚀 Innovación  
- **Flexibilidad de horarios:** Coincidencia personalizada entre disponibilidad de asesores y alumnos.  
- **Apoyo entre pares:** Comunidad que refuerza el aprendizaje mutuo.  
- **Originalidad:** Integra formación académica + créditos optativos en un mismo ecosistema.  

---

## 🎯 Objetivo  
**PeerHive** busca fortalecer la colaboración entre estudiantes de la carrera de software, conectando necesidades de asesoría con oportunidades de enseñanza, creando así una comunidad flexible, accesible y enriquecedora.  

---

## 🌟 Propuesta de Valor  
- **Diferenciador:** No es solo una plataforma de tutorías, es una **comunidad académica**.  
- **Beneficios clave:**  
  - Flexibilidad horaria.  
  - Cercanía entre estudiantes (mayor empatía y comprensión).  
  - Obtención de créditos optativos para asesores.  
  - Experiencia de aprendizaje disfrutable y accesible.  

---

## 📋 Requisitos  

### 👨‍🏫 Asesores  
- Contar con mínimo **180 créditos**.  
- No haber recursado la materia a asesorar.  
- Contar con un calendario de disponibilidad.  

### 🎓 Alumnos  
- Indicar disponibilidad de horario.  
- Seleccionar áreas/materias en las que necesitan apoyo.  

---

## ⚙️ Requisitos Funcionales  
1. **Registro e inicio de sesión:** Creación de cuentas seguras.  
2. **Perfil del usuario:** Datos académicos, áreas de conocimiento y necesidades.  
3. **Solicitudes de ayuda:** Envío de peticiones a asesores.  
4. **Agendamiento:** Programar sesiones de asesoría.  
5. **Mensajería directa:** Chat interno para coordinación.  

---

## 🔧 Requisitos No Funcionales  

### Rendimiento  
- Tiempo de respuesta < **2 segundos** incluso en picos.  
- Escalabilidad hasta **500 usuarios** iniciales.  

### Usabilidad  
- Navegación sencilla (**máx. 3 clics** para encontrar lo buscado).  
- Diseño consistente y claro.  

### Seguridad  
- Contraseñas encriptadas.  
- Datos personales privados.  
- Protección contra inyección **SQL** y **XSS**.  

### Mantenimiento  
- Respaldos diarios.  
- Disponibilidad mínima del **80%**.  

---

## 📌 Priorización (MoSCoW)  

- **Must-Have (debe tener):** Registro, login, perfiles, solicitud de asesoría, calendario, chat básico, seguridad.  
- **Should-Have (debería tener):** Recordatorios automáticos, métricas de desempeño, historial de sesiones.  
- **Could-Have (podría tener):** Videollamadas integradas, gamificación (puntos/recompensas).  
- **Won’t-Have (no tendrá):** Integración con sistemas externos en la primera versión.  

---

## 📑 Artefacto  

### 🔄 Proceso  
1. Registro de usuarios (alumno/asesor).  
2. Creación de perfil académico.  
3. Solicitud de asesoría.  
4. Coincidencia de horarios.  
5. Sesión de asesoría (online/presencial).  
6. Registro de horas y validación por parte de la coordinación.  

### 📂 Gestión del Proceso  
- Control de usuarios (base de datos segmentada).  
- Registro automático de sesiones.  
- Reportes para administrativos.  

### 📊 Métrica de contribución individual  
- Horas de asesoría impartidas.  
- Horas de asesoría recibidas.  
- Retroalimentación (valoración de sesiones).  
