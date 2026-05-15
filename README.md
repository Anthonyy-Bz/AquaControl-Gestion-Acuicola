# AquaControl - Sistema de Gestión Acuícola

AquaControl es una solución integral diseñada para la administración y monitoreo de granjas acuícolas, específicamente camaroneras. El sistema digitaliza el control de producción, sustituyendo registros manuales por una arquitectura moderna que asegura la trazabilidad desde la siembra hasta la cosecha.

## Contexto del Proyecto

Este sistema fue desarrollado de forma colaborativa como un proyecto de fin de ciclo. Mi contribución principal se centró en el desarrollo del Backend utilizando .NET Core, la gestión de la base de datos en SQL Server y la orquestación de servicios mediante contenedores Docker.

## Funcionalidades Principales

El sistema se divide en cuatro módulos interconectados:

- Gestión de Piscinas: Control de infraestructura, ubicación, capacidad y estados operativos.
- Control de Cultivos: Registro de siembras, especies y densidades poblacionales.
- Parámetros de Calidad: Monitoreo de variables críticas como pH, oxígeno, temperatura y salinidad.
- Registro de Alimentación: Control de dietas, tipos de alimento y cantidades suministradas.

## Tecnologías Utilizadas

- Backend: .NET Core Web API (C#)
- Frontend: Angular (Single Page Application)
- Base de Datos: SQL Server 2022
- Infraestructura: Docker y Docker Compose para orquestación de servicios
- Persistencia avanzada: Uso de Procedimientos Almacenados con inyección XML para transacciones masivas.

## Guía de Inicio Rápido

Para ejecutar el proyecto en un entorno local, se requiere tener instalado Docker Desktop y Node.js.

1. Clonar el repositorio.
2. Desplegar los servicios (API y Base de Datos) mediante el comando:
   docker-compose up -d
3. Inicializar la base de datos ejecutando el script SQL proporcionado en el contenedor de SQL Server.
4. En la carpeta del frontend, instalar dependencias con:
   npm install
5. Iniciar la aplicación mediante:
   ng serve

## Acceso al Sistema

Una vez iniciados los servicios, la aplicación web está disponible en http://localhost:4200 y la documentación de la API se puede consultar vía Swagger en el puerto configurado del backend.

---

Nota: Este proyecto tiene un carácter académico y profesional, diseñado para demostrar la integración de tecnologías modernas en la resolución de problemas reales del sector acuícola.
