# Form Implementation Templates / Formularios de Implementacion

## English

This repository contains three HTML intake forms used during the implementation of the TASS system. Clients complete the form that matches their plan and submit the information required to configure their setup, branding, workflows, and supporting assets.

### Included forms

- `TASS_Formulario_Starter.html`
- `TASS_Formulario_PRO.html`
- `TASS_Formulario_Elite.html`

### What these forms collect

- Agency and contact details
- Brand assets such as logos and colors
- Operational and commercial workflow information
- Reference files such as quote templates and supporting documents
- Additional onboarding details depending on the selected plan

### Form delivery

All three forms are connected to Web3Forms and use the project access key associated with the company mailbox:

- Destination email: `it.integral.solution@gmail.com`

### File uploads

The forms submit using `multipart/form-data` through JavaScript `FormData` so attached files can be delivered with the submission email whenever Web3Forms supports that field and file size.

### Usage

1. Open the desired HTML file in a browser.
2. Complete the form fields.
3. Attach logo, branding, or support files if needed.
4. Submit the form.

### Notes

- These forms are plain HTML files with embedded CSS and JavaScript.
- If you publish them online, make sure the hosting environment allows client-side requests to the Web3Forms endpoint.
- Large or multiple attachments may depend on the active Web3Forms plan and limits.

## Espanol

Este repositorio contiene tres formularios HTML de relevamiento usados durante la implementacion del sistema TASS. El cliente completa el formulario correspondiente a su plan y envia la informacion necesaria para configurar su sistema, branding, flujos de trabajo y archivos de soporte.

### Formularios incluidos

- `TASS_Formulario_Starter.html`
- `TASS_Formulario_PRO.html`
- `TASS_Formulario_Elite.html`

### Informacion que recopilan

- Datos de la agencia y de contacto
- Activos de marca como logos y colores
- Informacion operativa y comercial
- Archivos de referencia como plantillas de presupuestos y documentos de apoyo
- Detalles adicionales de onboarding segun el plan seleccionado

### Envio de formularios

Los tres formularios estan conectados a Web3Forms y usan la access key del proyecto asociada al correo de la empresa:

- Email de destino: `it.integral.solution@gmail.com`

### Carga de archivos

Los formularios envian los datos con `multipart/form-data` usando `FormData` en JavaScript para que los archivos adjuntos puedan viajar junto con el email de envio siempre que Web3Forms lo soporte para ese campo y tamano.

### Uso

1. Abrir el archivo HTML deseado en un navegador.
2. Completar los campos del formulario.
3. Adjuntar logos, branding o archivos de apoyo si hace falta.
4. Enviar el formulario.

### Notas

- Son archivos HTML puros con CSS y JavaScript embebidos.
- Si se publican online, el hosting debe permitir solicitudes cliente al endpoint de Web3Forms.
- Los archivos grandes o multiples pueden depender del plan activo y de los limites de Web3Forms.
