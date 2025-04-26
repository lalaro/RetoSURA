# RetoSURA
Reto 05 - Automatizar Facturación de Reclamaciones en el Seguro SOAT Autos - Alexis - Desarrollo Seg

Este proyecto propone una solución tecnológica moderna para mejorar el proceso de facturación y reclamaciones médicas del SOAT en SURA. A través de una arquitectura basada en microservicios y desplegada en la nube, se busca cerrar la brecha operativa entre la IPS y SURA, garantizando trazabilidad, eficiencia y seguridad.

## 🎯 Objetivo del Proyecto

Diseñar una plataforma unificada que permita la integración entre las IPS y SURA, facilitando la gestión de documentos, la validación de facturas, la trazabilidad de trámites y la automatización de procesos críticos.

## 🏗️ Arquitectura Propuesta

- **Frontend**: Aplicación web en Angular.
- **Backend**: Microservicios con Spring Boot.
- **Mensajería**: RabbitMQ para desacoplar procesos y garantizar escalabilidad.
- **Persistencia**: PostgreSQL en la nube.
- **Contenerización y orquestación**: Docker + Kubernetes (AKS).
- **Infraestructura y despliegue**: Azure DevOps.

## 🧠 Justificación Tecnológica

- **Angular**: Para construir una experiencia de usuario dinámica e intuitiva.
- **Spring Boot**: Por su robustez, modularidad y escalabilidad para servicios backend.
- **RabbitMQ**: Permite manejar procesos pesados (como auditorías o validaciones) de forma asíncrona.
- **Kubernetes y Docker**: Aseguran escalabilidad, alta disponibilidad y facilidad de mantenimiento.
- **Azure DevOps**: Facilita el control de versiones, CI/CD y gestión de despliegues.

## ✅ Beneficios de la Plataforma

- Reducción de errores humanos en el proceso de facturación.
- Eliminación de reprocesos y tiempos muertos.
- Integración en tiempo real entre IPS y SURA.
- Mayor transparencia y trazabilidad.
- Escalabilidad y disponibilidad garantizadas con tecnologías cloud-native.

## 🔍 Monitoreo y Trazabilidad

- Integración de herramientas de observabilidad (Grafana, Prometheus, ELK Stack).
- Registro de eventos y seguimiento de transacciones clave en la plataforma.
- Alertas automáticas ante errores o anomalías operativas.