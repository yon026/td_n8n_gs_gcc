# td_n8n_gs_gcc
Proyecto de automatización y conectividad: Aplicación móvil en App Inventor conectada a un servidor local n8n a través de SSH y contenedores Docker.

# Proyecto de Conexión IoT con n8n y App Inventor

Este repositorio contiene la integración de una aplicación móvil desarrollada en **MIT App Inventor** con una instancia automatizada de **n8n**, corriendo sobre Docker en una máquina virtual de VirtualBox.

## 🛠️ Arquitectura del Sistema
* **Servidor de Automatización:** n8n ejecutándose dentro de contenedores Docker.
* **Entorno Virtual:** Servidor n8n alojado en VirtualBox.
* **Conexión de Red:** Host local (Linux Mint) conectado de forma segura mediante un **Túnel SSH**.
* **Interfaz de Usuario:** App Inventor para el envío (inserción) y recepción (lectura) de datos mediante peticiones HTTP (Webhooks).

## 📄 Documentación del Proceso
Siguiendo los requerimientos de la consigna, se ha generado una guía detallada paso a paso que documenta la configuración del entorno, la creación de credenciales y el flujo de los datos.

👉 **[Haga clic aquí para ver la Documentación en Google Docs](https://docs.google.com/document/d/18xEEFwtDNuUyxajxIomVVXGko5F3AgC__rCKxg5NMoQ/edit?usp=sharing)**

### Resumen de lo documentado en el archivo:
1. **Configuración de Red e Infraestructura:** Levantamiento de n8n en Docker y apertura de puertos mediante el túnel SSH desde Linux Mint.
2. **Configuración de Credenciales:** Capturas de pantalla y pasos detallados de la seguridad en n8n.
3. **Flujo en App Inventor:** Bloques de código y lógica utilizada para realizar operaciones de lectura e inserción de datos.
