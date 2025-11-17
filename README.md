# Sistema de Pedidos - Cafetería Universitaria

## 📌 Descripción del Caso
El sistema consiste en una aplicación web para la cafetería universitaria que permite registrar pedidos, gestionar el menú, calcular totales y generar comprobantes. Está dirigido al personal de cafetería y estudiantes para mejorar el proceso de atención y reducir tiempos de espera.

---

## 🎯 Objetivos del Proyecto
- Optimizar la gestión de pedidos y tiempos de atención.
- Facilitar procesos de cálculo automático de totales.
- Garantizar el funcionamiento estable y accesible del sistema.
- Contar con una base para futuras mejoras (notificaciones, seguimiento, etc.).

---

## 📋 Requerimientos

### ✔️ Requerimientos Funcionales
| ID | Requerimiento | Tipo |
|----|---------------|------|
| RF1 | Registrar pedidos | Esencial |
| RF2 | Calcular el total | Esencial |
| RF3 | Gestión de menú | Esencial |
| RF4 | Generar comprobante | Esencial |
| RF5 | Cancelar pedido | Deseable |

### ✔️ Requerimientos No Funcionales
| ID | Requerimiento | Tipo |
|----|---------------|------|
| RNF1 | Tiempo de respuesta | Rendimiento |
| RNF2 | Facilidad de uso | Usabilidad |
| RNF3 | Backup de datos | Confiabilidad |

---

## 🧪 Tabla de Pruebas

### 🔹 Pruebas Unitarias
| ID | Req. | Datos de Entrada | Resultado Esperado | Resultado Obtenido |
|----|------|----------------|------------------|------------------|
| PU1 | RF2 | Café $2 + Sándwich $5 | Total $7 | $7 ✅ |
| PU2 | RF4 | Pedido con 3 productos | Comprobante generado | Correcto ✅ |
| PU3 | RF1 | Agua x3 | Pedido registrado | Correcto ✅ |

### 🔹 Pruebas de Validación
| ID | Req. | Datos de Entrada | Resultado Esperado | Resultado Obtenido |
|----|------|----------------|------------------|------------------|
| PV1 | RNF1 | 100 pedidos simultáneos | Tiempo < 2s | 1.8s ✅ |
| PV2 | RNF3 | Falla del sistema | Recuperar datos | Correcto ✅ |

---

## 🔧 Tipo de Mantenimiento Propuesto
El mantenimiento aplicado al sistema es principalmente:

### ➤ **Perfectivo**
Porque se busca **mejorar** funciones esenciales y la experiencia del usuario, como la gestión de pedidos, el cálculo del total y la usabilidad.

También puede aplicarse **Correctivo** para mejorar errores como el manejo de cancelaciones.

---

## 🔄 Reflexión sobre el Control de Versiones
El control de versiones permite gestionar cambios, mantener un historial del desarrollo y evitar pérdida de información. Garantiza que las actualizaciones en los requerimientos, pruebas y correcciones puedan ser trazadas y verificadas fácilmente, contribuyendo a una **mayor calidad del software** y un **mantenimiento más eficiente**.

---

## 🙌 Conclusión
El uso de buenas prácticas en requerimientos, pruebas y control de versiones asegura que el sistema cumpla con las necesidades del usuario final y pueda evolucionar de forma ordenada y segura.

