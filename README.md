# Proyecto Power BI: Tractchun

Este proyecto forma parte de un curso de **Udemy**, dictado por **Javier Gómez**, a quien agradezco por sus claras explicaciones y la naturalidad con la que presenta los temas.  
El objetivo principal es desarrollar un **reporte interactivo en Power BI** para **Tractchun**, una compañía ficticia de la industria manufacturera.  

## Descripción del Proyecto

Tractchun cuenta con un equipo de Tecnología de Información (TI) encargado de gestionar tickets relacionados con sus tecnologías de oficina (hardware, software, sistemas, etc.). El gerente del equipo solicitó un análisis detallado de los datos de tickets para monitorear y revisar áreas de mejora en su servicio.  

Con una base de datos de **97,948 tickets**, se realizó un análisis utilizando **Power BI**, integrando datos extraídos del sistema de tickets y del departamento de Recursos Humanos.  

## Proceso de Desarrollo

### 1. Modelado de Datos
Se utilizó un **esquema estrella**, con los siguientes beneficios:  
- Manejo eficiente de grandes volúmenes de datos.  
- Mayor optimización para interacciones rápidas con los reportes.  
- Facilidad para realizar modificaciones en la estructura de los datos.  
- Consumo reducido de memoria en comparación con otros esquemas.  

### 2. Tabla Calendario
La tabla calendario fue clave para trabajar con períodos de tiempo y generar análisis más detallados. Sus aplicaciones incluyen:  
- Visualizaciones basadas en períodos (mensuales, diarios, etc.).  
- Obtención de resultados por períodos específicos (mensual, cuatrimestral, etc.).  
- Mejora en la precisión de funciones relacionadas con fechas.  

### 3. Visualizaciones y Análisis
En el reporte se incluyeron las siguientes visualizaciones:  
- **Total de tickets por calificación**: Basado en la satisfacción del empleado con el servicio de los agentes.  
- **Total de tickets por días abiertos**: Agrupados en 4 categorías (0-1 días, 2-5 días, 6-9 días, +10 días).  
- **Total de tickets por categoría**: Clasificados por sistemas, hardware, software, acceso/login, entre otros.  
- **Total de tickets por fecha**: Permitiendo un análisis temporal de los tickets gestionados.  

### 4. KPIs Personalizados
Se crearon indicadores clave de desempeño (KPIs) utilizando **DAX**:  
- Total de tickets.  
- Promedio de satisfacción.  
- Promedio de días abiertos.  
- Tickets por agente.  

### 5. Interactividad del Reporte
Se añadieron filtros dinámicos e interacciones avanzadas:  
- Filtros por año, mes y agente.  
- Segmentación por tipo de ticket mediante bookmarks.  
- Alternancia entre temas claro y oscuro para mejorar la experiencia de usuario.

<p align="center">
  <img width="100%" height="100%" src="https://res.cloudinary.com/dq9faptjc/image/upload/v1737552899/1_qqrg2z.png">
</p>
<p align="center">
  <img width="100%" height="100%" src="https://res.cloudinary.com/dq9faptjc/image/upload/v1737552899/2_j3ca5g.png">
</p>
<p align="center">
  <img width="100%" height="100%" src="https://res.cloudinary.com/dq9faptjc/image/upload/v1737552899/3_e2scvf.png">
</p>
<p align="center">
  <img width="100%" height="100%" src="https://res.cloudinary.com/dq9faptjc/image/upload/v1737552899/4_pxi3wz.png">
</p>
<p align="center">
  <img width="100%" height="100%" src="https://res.cloudinary.com/dq9faptjc/image/upload/v1737552899/5_su9vcv.png">
</p>

## Próximos Pasos
Actualmente estoy trabajando en:  
- Realizar un balance de las actividades de los agentes de TI.  
- Revisar la carga de trabajo de los agentes con base en las categorías de tickets gestionados.  

## Conclusión
Este proyecto ha sido un excelente ejercicio para aplicar mis habilidades en análisis de datos, visualización y optimización de procesos con Power BI.  
Si tienes sugerencias o comentarios, no dudes en contactarme! Gracias por visitar mi repositorio!
