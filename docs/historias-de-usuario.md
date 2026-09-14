# Historias de Usuario (Backlog Ágil)
**Sistema:** PROYECTO IQUAL (Sistema de Gestión Escolar - SGE)  
**Materia:** Proyecto Informático I - 4° Año Computación  
**Marco:** Buenos Aires Aprende (CABA)  

---

## Historias de Usuario 🟡

*Desarrollo formal bajo la fórmula: **Como [perfil], quiero [funcionalidad], para [beneficio]**, acompañado de las 3 C (Tarjeta, Conversación y Confirmación).*

### 🟡 US01: Módulo Objetos Perdidos
* **Historia de Usuario:** Como **Preceptor**, quiero **publicar las pertenencias extraviadas que se encuentran en la escuela**, para que **los alumnos puedan identificarlas y solicitar su devolución reduciendo la acumulación en preceptoría**.
* **Criterios de Aceptación (Confirmación):**
  * `1.1` La carga requiere de forma obligatoria un título descriptivo y la categoría del objeto.
  * `1.2` Preceptoría puede marcar un objeto como "devuelto" o "archivado" para quitarlo del catálogo público.
  * `1.3` El alumno debe completar un campo de texto con la descripción detallada de su prueba antes de confirmar la solicitud.

### 🟡 US02: Módulo Reporte de Higiene/Mantenimiento
* **Historia de Usuario:** Como **Alumno**, quiero **reportar una avería o falta de higiene en un sector de la escuela**, para que **las autoridades y personal de maestranza conozcan el problema y ordenen su reparación**.
* **Criterios de Aceptación (Confirmación):**
  * `2.1` El formulario ofrece desplegables para seleccionar el sector (ej. "Baño PB") y la categoría ("Higiene", "Rotura").
  * `2.2` Permite adjuntar un comentario descriptivo del desperfecto.
  * `2.3` La pantalla despliega la fecha, hora y responsable del último mantenimiento realizado en el área.

### 🟡 US03: Módulo Buffet Paralelo y Recaudación
* **Historia de Usuario:** Como **Alumno de último año**, quiero **publicar productos a la venta en el buffet de la aplicación**, para **recaudar fondos destinados a financiar nuestro viaje de egresados**.
* **Criterios de Aceptación (Confirmación):**
  * `3.1` Permite ingresar nombre del producto, precio, stock inicial y la meta grupal asociada.
  * `3.2` Cada reserva de compra desde la app descuenta automáticamente el stock disponible.
  * `3.3` Incluye una opción clara para registrar donaciones directas destinadas al objetivo del grupo.

### 🟡 US04: Módulo Planillas Digitales de Taller
* **Historia de Usuario:** Como **Profesor de Taller**, quiero **registrar en forma digital el préstamo de computadoras y tableros**, para **eliminar el uso de planillas de papel manuales y evitar pérdidas de equipamiento**.
* **Criterios de Aceptación (Confirmación):**
  * `4.1` El formulario requiere obligatoriamente: Carro (C4/C5), # de máquina o tablero, Nombre del Alumno, Curso, División y Profesor.
  * `4.2` Valida que un mismo recurso no esté asignado a dos alumnos al mismo tiempo en el mismo bloque horario.
  * `4.3` Provee un buscador rápido por número de recurso para auditar asignaciones activas.

### 🟡 US05: Módulo Reserva de Sectores
* **Historia de Usuario:** Como **Docente**, quiero **reservar el laboratorio o la biblioteca mediante un calendario en línea**, para **asegurar la disponibilidad del espacio sin entorpecer a otros profesores**.
* **Criterios de Aceptación (Confirmación):**
  * `5.1` Muestra un calendario mensual interactivo codificado por colores (Verde: Libre, Rojo: Ocupado).
  * `5.2` Invalida solicitudes superpuestas en el mismo módulo horario notificando los datos del docente ocupante.
  * `5.3` Permite a las autoridades escolares autorizar o cancelar solicitudes cargadas.

### 🟡 US06: Módulo Educación Física
* **Historia de Usuario:** Como **Alumno**, quiero **inscribirme a la cursada de una disciplina deportiva**, para **cumplir con la materia registrando un horario compatible con mis clases de taller**.
* **Criterios de Aceptación (Confirmación):**
  * `6.1` Al registrarse, el alumno ingresa obligatoriamente su Curso y División para heredar su franja de teoría/taller.
  * `6.2` El sistema cruza los horarios y rechaza automáticamente inscripciones deportivas que causen superposiciones.
  * `6.3` El sistema limita los cupos máximos de inscripción por deporte según la capacidad organizativa.
