# Plan de Trabajo
## Fase 1: Análisis (2–3 días)
**Objetivo:** comprender las necesidades del negocio y definir alcance mínimo viable.
**Tareas:**
1. Reunión inicial con el dueño de la refaccionaria:
    - Detectar necesidades principales (inventario, clientes frecuentes, ventas).
    - Recabar datos básicos (productos principales, proveedores, tipo de clientes).
2. Levantamiento de procesos actuales:
    - Cómo registran ventas.
    - Cómo controlan inventario.
    - Cómo se comunican con clientes.
3. Definir **alcance del proyecto Jam**:
    - Sitio web: catálogo, contacto, ubicación.
    - CRM: registro clientes + puntos.
    - ERP: inventario básico + compras.
4. Documentar requerimientos en un breve documento (máximo 2 páginas).
**Entregable:** Documento de requerimientos iniciales (con diagramas de procesos simples).
## Fase 2: Diseño (3–4 días)
**Objetivo:** planear la arquitectura ligera, interfaces y flujos del sistema.
**Tareas:**
1. **Diseño del sitio web:**
    - Mockups de la página principal, catálogo, contacto y promociones.
2. **Modelo de datos CRM:**
    - Tabla clientes: nombre, WhatsApp, historial de compras, puntos.
    - Flujo: compra → suma puntos → mensaje automático.
3. **Modelo de datos ERP:**
    - Tabla inventario: código, nombre, stock actual, stock mínimo, proveedor.
    - Flujo: venta → descuenta stock → alerta bajo inventario → orden de compra.
4. Selección de herramientas:
    - Sitio: HTML/React/WordPress.
        
    - CRM + ERP MVP: Google Sheets + AppSheet o Zoho CRM + dashboards de inventario.
        
    - Automatización: Zapier/Make/n8n para mensajes de puntos.
        

**Entregables:**

- Mockups del sitio.
    
- Diagramas de flujo de CRM y ERP.
    
- Modelo de datos inicial (tablas).
## **Fase 3: Desarrollo (5–6 días)**

**Objetivo:** construir los módulos definidos y dejar un prototipo funcional.

**Tareas:**

1. Construcción del sitio web:
    
    - Página principal, catálogo, contacto, Google Maps, botón de WhatsApp.
        
2. Configuración del CRM:
    
    - Base de clientes en Google Sheets/AppSheet.
        
    - Panel para registrar compra y sumar puntos.
        
3. Configuración del ERP ligero:
    
    - Tabla de inventario con stock y alertas de mínimo.
        
    - Registro de proveedores y flujo de compras.
        
4. Integración mínima entre módulos:
    
    - Venta → afecta inventario (ERP).
        
    - Venta → suma puntos cliente (CRM).
        
5. Registro del negocio en plataforma **Coppel Emprende** (requisito del Jam).
    

**Entregable:** Prototipo integrado (sitio web + CRM + ERP mínimo).
## **Fase 4: Pruebas (2–3 días)**

**Objetivo:** validar que todo funcione y sea fácil de usar para el dueño.

**Tareas:**

1. Pruebas del sitio web:
    
    - Navegación, formulario de contacto, botón WhatsApp, catálogo.
        
2. Pruebas del CRM:
    
    - Alta de cliente, registro de compra, suma de puntos, envío de mensaje.
        
3. Pruebas del ERP:
    
    - Venta → descuenta stock.
        
    - Inventario bajo → genera alerta de reabastecimiento.
        
4. Revisión con el dueño del negocio (feedback directo).
    
5. Ajustes menores de usabilidad y errores detectados.
    

**Entregable:** Registro de pruebas (documento con capturas y observaciones).
## **Fase 5: Implementación (2–3 días)**

**Objetivo:** poner el sistema en marcha y entregar documentación.

**Tareas:**

1. Subir el sitio web a hosting gratuito o económico.
    
2. Dar acceso al dueño a las herramientas (CRM + ERP + manuales básicos).
    
3. Capacitación breve (30–40 min) para explicar cómo:
    
    - Consultar inventario.
        
    - Registrar clientes y sumar puntos.
        
    - Ver reportes básicos.
        
4. Preparar entregables del Jam:
    
    - **Video pitch (5 minutos)** mostrando todo el flujo.
        
    - **Documento PDF** con descripción, capturas y ligas.
        

**Entregables:**

- Sitio web en línea.
    
- CRM y ERP en uso.
    
- Manual rápido de usuario (PDF).
    
- Video + PDF final para el Jam.
___
#Proyecto 