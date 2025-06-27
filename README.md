# Análisis de Churn en Clientes de Telecomunicaciones

Este proyecto analiza el comportamiento de abandono de clientes (*churn*) en una empresa de telecomunicaciones, con el objetivo de identificar patrones y variables que influyen en la retención o pérdida de clientes.

## Objetivo

El análisis busca responder preguntas clave como:
- ¿Qué características comparten los clientes que abandonan?
- ¿Existen patrones por género, tipo de contrato o método de pago?
- ¿Cómo influyen variables como la antigüedad del cliente (*tenure*) o el monto de facturación?

---

## Herramientas Utilizadas

- **Python**
- **pandas**: Manipulación y análisis de datos tabulares.
- **numpy**: Operaciones matemáticas y estadísticas.
- **matplotlib**: Visualización de datos con gráficos básicos.
- **seaborn**: Visualización avanzada con enfoque estadístico.

---

## Análisis Realizado

### 1. Distribución General de Churn
- El 26.5% de los clientes se dieron de baja.
- El 73.5% permanecieron con el servicio.

### 2. Churn por Tipo de Contrato
- El churn es mucho mayor en contratos **mensuales (month-to-month)**.
- Contratos de **un año** o **dos años** retienen significativamente más clientes.

### 3. Churn por Método de Pago
- **Cheques electrónicos** tienen la tasa más alta de abandono.
- **Pagos automáticos** (tarjeta o transferencia) muestran mayor retención.

### 4. Churn por Género
- No se observan diferencias significativas entre hombres y mujeres.

### 5. Tenure (Antigüedad del Cliente)
- Los clientes que se van tienen una antigüedad media de **18 meses**, contra **37.6 meses** para quienes permanecen.
- La mayoría de los abandonos ocurren en los primeros 20 meses.

### 6. Cargos Totales (`Charges.Total`)
- Clientes que se quedan acumulan más cargos totales, reflejando mayor tiempo con la empresa.

### 7. Cargos Mensuales (`Charges.Monthly`)
- Clientes con **facturación mensual alta** tienden a abandonar más, posiblemente por insatisfacción con el valor percibido.

---

## Conclusiones

- Los clientes nuevos, con contratos mensuales y pagos no automáticos, presentan mayor riesgo de churn.
- Es recomendable diseñar estrategias de retención para clientes en sus primeros meses y aquellos con altos cargos mensuales.
- La fidelización debería enfocarse especialmente en usuarios de contratos flexibles y con métodos de pago manuales.

---



