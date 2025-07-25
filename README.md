# Chatbot AWS GenAI LLM

Chatbot de IA generativa listo para empresas con capacidades RAG.

Visión general
El Chatbot AWS GenAI LLM es una solución lista para producción que permite a las organizaciones implementar un chatbot seguro y con múltiples funciones, impulsado por modelos de lenguaje de gran tamaño (LLMs) con capacidades de Generación Aumentada por Recuperación (RAG).

Características clave

Compatibilidad con múltiples LLMs: Amazon Bedrock (Claude, Llama 2), SageMaker y endpoints de modelos personalizados

Integración con Nexus Gateway: Conéctate a Nexus Gateway para acceder a modelos adicionales

Implementación RAG completa: Conexión a diversas fuentes de datos para respuestas con contexto

Seguridad empresarial: Controles de acceso detallados, registros de auditoría y cifrado de datos

Memoria de conversación: Historial completo de conversaciones con almacenamiento persistente

Interfaz web y acceso por API: Interfaz moderna en React y endpoints API para integración

Optimización de costos: Seguimiento del uso de tokens y funciones de gestión de costos

Flexibilidad de despliegue: Múltiples opciones de implementación según tus necesidades

Primeros pasos
Este blueprint despliega la solución completa del Chatbot AWS GenAI LLM en tu cuenta de AWS.

Requisitos previos

Cuenta de AWS con los permisos adecuados

AWS CLI configurado con credenciales

Node.js 18+ y npm

Python 3.8+

Despliegue
El proceso de despliegue está completamente automatizado mediante AWS CDK y SeedFarmer.

Arquitectura
La arquitectura de la solución incluye:

Amazon Bedrock para acceso a LLMs

Amazon OpenSearch para almacenamiento vectorial

Amazon S3 para almacenamiento de documentos

Amazon Cognito para autenticación

AWS Lambda para procesamiento serverless

Amazon API Gateway para acceso por API

Interfaz web basada en React

Documentación
Para la documentación completa, visita el repositorio en GitHub.

