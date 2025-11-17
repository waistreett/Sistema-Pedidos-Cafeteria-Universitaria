# Sistema de Pedidos - Cafetería Universitaria

## 1. Descripción del Sistema

El Sistema de Pedidos para Cafetería Universitaria es una aplicación diseñada para facilitar y agilizar el proceso de compra de alimentos y bebidas en la cafetería del campus. Permite a los estudiantes, docentes y personal administrativo consultar el menú disponible, realizar pedidos y pagar de manera rápida y sencilla desde sus dispositivos móviles o desde una terminal dentro del establecimiento.

El sistema organiza los pedidos en tiempo real y los envía directamente al área de cocina, lo que reduce significativamente los tiempos de espera y evita aglomeraciones en la cafetería. Los usuarios pueden seleccionar sus opciones favoritas y recibir notificaciones sobre el estado de su pedido, lo que les permite planificar su tiempo de manera más eficiente.

Además, el sistema ofrece herramientas para que el personal de la cafetería administre productos, controle inventarios y registre ventas, mejorando la eficiencia en el servicio y la atención al cliente. Los administradores pueden acceder a informes y análisis de datos para tomar decisiones informadas sobre el menú, promociones y gestión de recursos.

Con esta aplicación, la experiencia de compra en la cafetería universitaria se vuelve más eficiente, conveniente y satisfactoria para todos los usuarios.

---

## 2. Análisis del Problema

### 2.1 Ausencia de Seguimiento del Pedido

El sistema actual no proporciona un mecanismo para rastrear el estado del pedido una vez realizado.

**Tipo de Mantenimiento:** Perfectivo

**Impacto directo en el estudiante:**

* Incertidumbre por el tiempo de espera.
* Ansiedad por no saber si su pedido está en proceso, listo o perdido.
* Pérdida de tiempo valioso.

**Impacto directo en el personal:**

* Saturación en el mostrador de entrega.
* Estrés por la presión de los clientes esperando.
* Interrupciones constantes por consultas repetitivas.

**Consecuencias:**

* Ineficiencia en gestión de tiempos de preparación.
* Flujo de trabajo interrumpido constantemente.
* Posibles confusiones en secuencia de pedidos.

### 2.2 Ausencia de Sistema de Navegación

No existen notificaciones automáticas sobre el estado del pedido, obligando la comunicación presencial.

**Tipo de Mantenimiento:** Perfectivo

**Comunicación ineficiente:**

* Los estudiantes deben permanecer presentes para recibir actualizaciones.
* Falta de confirmaciones automáticas.
* No hay alertas sobre el estado del pedido.

**Experiencia del usuario:**

* Frustración por falta de información en tiempo real.
* Incertidumbre constante sobre tiempos estimados.
* Sensación de desorganización del servicio.

**Consecuencias:**

* Personal gasta tiempo repitiendo información.
* Sin registro histórico de notificaciones.
* Imposibilidad de notificar retrasos o cambios en pedidos.

---

## 3. Tipos de Mantenimiento

El mantenimiento de software es el proceso de modificar un sistema después de su entrega con el fin de corregir, mejorar, adaptar o prevenir fallos.

**Tipos:**

* **Correctivo:** Corrige fallas detectadas en el software.
* **Adaptativo:** Adapta el software a cambios del entorno.
* **Perfectivo:** Optimiza el rendimiento o añade funcionalidades.
* **Preventivo:** Previene futuros problemas y mejora estructura interna.

### Costos del Mantenimiento

* Representan entre 60% y 80% del costo total de vida del software.

**Factores que aumentan el costo:**

* Código mal estructurado
* Falta de documentación
* Cambios frecuentes en requisitos
* Tecnologías obsoletas

**Factores que reducen el costo:**

* Buen diseño inicial
* Documentación clara
* Programación modular
* Uso de control de versiones

### Etapas del mantenimiento según Sommerville

* Análisis de solicitudes de cambio
* Comprensión del software
* Modificación del software
* Pruebas del cambio
* Entrega y documentación

### Etapas del mantenimiento según Pressman

* Identificación y análisis del problema
* Estudio de impacto
* Diseño del cambio
* Implementación
* Pruebas de regresión
* Actualización de documentación
* Distribución de versión

---

### 3.1 Tipos de Mantenimiento Aplicables

| Tipo de mantenimiento | Descripción                                                    |
| --------------------- | -------------------------------------------------------------- |
| Perfectivo            | Mejora funcionalidades, rendimiento y experiencia del usuario. |
| Correctivo            | Elimina errores detectados en el sistema.                      |

---

## 4. Justificación Teórica y Técnica

### 4.1 Mantenimiento Perfectivo

| Base Teórica                         | Justificación Técnica                                                                                 |
| ------------------------------------ | ----------------------------------------------------------------------------------------------------- |
| Mejora de funcionalidad y eficiencia | - Nuevos métodos de pago<br>- Roles y paneles de gestión<br>- Seguimiento de pedidos y notificaciones |
| Mejora de la usabilidad              | - Implementación de modo nocturno                                                                     |

### 4.2 Mantenimiento Correctivo

| Base Teórica          | Justificación Técnica                               |
| --------------------- | --------------------------------------------------- |
| Corrección de errores | - Cancelación de pedido no registrada correctamente |

---

## 5. Cambio Funcional Propuesto

### 5.1 Sistema Integral de Seguimiento y Notificaciones

Transformación del sistema actual en una plataforma moderna con:

* Seguimiento en tiempo real
* Notificaciones multicanal
* Pagos digitales expandidos
* Modo nocturno y accesibilidad

### 5.2 Módulo de Seguimiento en Tiempo Real

* Barra de progreso: *Recibido – En preparación – Listo – Entregado*
* Temporizador inteligente
* Actualizaciones automáticas

### 5.3 Sistema de Notificaciones Multicanal

* Notificaciones PUSH
* SMS como alternativa
* Alertas estratégicas según ciclo del pedido

### 5.4 Pagos Digitales Expandidos

* Tarjetas débito/crédito
* Billetera digital universitaria
* Cashback y recargas online
* Tokenización y seguridad bancaria

### 5.5 Modo Nocturno y Temas Visuales

* Modo oscuro y sepia
* Contraste accesible
* Escalabilidad de texto

### 5.6 Flujo de Usuario Mejorado e Impacto Técnico

* Arquitectura modular con microservicios
* APIs RESTful documentadas

### 5.7 Plan de Implementación por Fases

* Transición progresiva y con mínimo impacto operativo

---

## 6. Reflexión Final

El desarrollo del sistema de pedidos universitarios demuestra cómo la ingeniería de software puede mejorar procesos reales. La automatización reduce tiempos de espera, optimiza recursos y mejora la experiencia del usuario.

El proyecto fortalece habilidades técnicas y de gestión, demostrando que el software es una herramienta clave para la innovación institucional y el progreso social.
