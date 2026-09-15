# Especificación de Requerimientos
**Sistema:** PROYECTO IQUAL® (Sistema de Gestión Escolar-SGE)  
**Materia:** Proyecto Informático I-4° Año Computación  
**Marco:** Buenos Aires Aprende (CABA)  

---

## 1.Requerimientos Funcionales (RF) 🔵

*Procesos, tareas y funciones operativas obligatorias del software.*

| ID | Nombre | Descripción |
| :--- | :--- | :--- |
| **RF01** | Publicación de Objetos Perdidos | El sistema debe permitir a las autoridades (preceptores) cargar fotografías, títulos y descripciones de las pertenencias extraviadas encontradas en la escuela. |
| **RF02** | Reclamo con Prueba de Pertenencia | El sistema debe solicitar al alumno la redacción obligatoria de una descripción/prueba de pertenencia antes de habilitar el retiro físico en preceptoría. |
| **RF03** | Reporte de Incidentes de Higiene/Infraestructura | El sistema debe permitir a los usuarios reportar averías (roturas, falta de higiene) seleccionando el sector escolar mediante listas desplegables. |
| **RF04** | Trazabilidad de Limpieza Sanitaria | El sistema debe mostrar el registro del último horario de limpieza realizado en el sector y el nombre del personal responsable. |
| **RF05** | Catálogo de Buffet Paralelo | El sistema debe permitir a los alumnos de último año publicar productos (tortas, alfajores) especificando precio, stock y el objetivo grupal de recaudación. |
| **RF06** | Registro de Donaciones Directas | El sistema debe ofrecer una opción digital para registrar aportes monetarios voluntarios destinados a metas grupales (ej. viaje de egresados). |
| **RF07** | Control Digital de Carros de Computación | El sistema debe permitir a los profesores registrar el préstamo de computadoras capturando: número de carro (C4/C5), máquina (#), alumno, curso, división y profesor solicitante. |
| **RF08** | Control Digital de Tableros de Dibujo | El sistema debe proveer un registro digital idéntico al RF07 para la asignación e inventario de los tableros de dibujo técnico del taller. |
| **RF09** | Reserva Interactiva de Sectores | El sistema debe ofrecer un calendario mensual para que los docentes soliciten el uso de la biblioteca y del laboratorio de química. |
| **RF10** | Bloqueo de Superposición de Sectores | El sistema debe rechazar de forma automática las solicitudes de reserva que coincidan en el mismo sector y módulo horario. |
| **RF11** | Inscripción a Educación Física | El sistema debe permitir a los alumnos inscribirse a una disciplina deportiva seleccionando día, turno u horario. |
| **RF12** | Validación Cruzada de Horarios Escolares | El sistema debe bloquear la inscripción a Educación Física si la franja horaria seleccionada coincide con las clases teóricas o de taller del curso del alumno. |

---

## 2.Requerimientos No Funcionales (RNF) 🟢

*Atributos de calidad,restricciones técnicas e infraestructura del sistema.*

* **RNF01 (Usabilidad):** La interfaz debe ser intuitiva, amigable y adaptable, siguiendo los principios de consistencia y diseño minimalista para usuarios con distinto nivel técnico.
* **RNF02 (Seguridad):** Las contraseñas de los usuarios deben guardarse cifradas en la base de datos local y los formularios deben contar con validaciones para prevenir inyecciones de código (SQL Injection).
* **RNF03 (Eficiencia/Rendimiento):** Las búsquedas en la base de datos (disponibilidad de sectores y recursos de taller) deben procesarse en un tiempo inferior a 2 segundos.
* **RNF04 (Escalabilidad y Modularidad):** El código fuente debe estructurarse de manera modular para permitir la incorporación de futuros módulos administrativos sin afectar el núcleo del sistema.
