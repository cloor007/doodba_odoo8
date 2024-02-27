# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com), and this project
adheres to [Semantic Versioning](https://semver.org).

## 2022-12-27

### Added

- Initial version

## 2023/02/07

### Added

- Actualizacion 07/02/2023

## 2023/03/07

### Added

- Actualizacion 07/03/2023

## 2023/03/28

### Added

- Actualizacion 28/03/2023 en imagen de doodba base por actualizacion de librerias

### Actualizacion 25/04/2023

- Correccion en importacion txt
- Chater en anticipos

### Actualizacion 20/06/2023

- actualizaciones acumuladas, parser, pedidos desde aldelo, fecha de anticipos

### Actualizacion 04/07/2023

- aldelo_conector: productos alternativos en recetas

### Actualizacion 25/07/2023

- ruta de jasper PID

### Actualizacion 01/08/2023

- Actualizaciones varias en contabilidad/aldelo(cierres de periodos)

### Actualizacion 15/08/2023

- Actualizaciones varias en contabilidad/aldelo(no cancelar picking de facturas)

### Actualizacion 22/08/2023

- Orden en reporte de cartera
- oculta padding de autorizaciones

### Actualizacion 29/08/2023

- Limitar caracteres en informacion adicional de xml

### Actualizacion 05/09/2023

- Corregir tarifa de iva en xml electronico
- formato A4 del banco bolivariano

### Actualizacion 19/09/2023

- Aldelo: corregir recetas sin componentes
- docker: soporte para multiples BD y ejecutar tareas cron

### Actualizacion 03/10/2023

- Aldelo: estructura y Reporte para horas trabajadas traidas desde aldelo

### Actualizacion 10/10/2023

- Contabilidad: Transferencias internas soporte para devoluciones
- Contabilidad: Transferencias internas correccion para procesar 2 veces documento si
  varios usuarios tienen abiertos el mismo documento

### Actualizacion 17/10/2023

- Contabilidad: Ajuste en formato de cheques
- Aldelo: mejora en mensaje de modificadores con componentes que no tienen stock

### Actualizacion 24/10/2023

- Contabilidad: pasar cuentas analiticas en pagos(cientes, proveedores y multiples)

### Actualizacion 07/11/2023

- Contabilidad: agregar producto en recibo de compras y ventas
- aldelo_connector_web: pasar la fecha de entrega del pedido a la factura

### Actualizacion 21/11/2023

- Contabilidad: Soporte para no objeto de IVA, y correccion de ICE
- Contabilidad: Banner en pie de pagina de RIDE

### Actualizacion 02/12/2023

- Contabilidad: Tarea cron para validar pagos del sistema externo de espoltel

### Actualizacion 06/12/2023

- doodba: Agregar parametro enable_email_sending para enviar correos electronicos

### Actualizacion 12/12/2023

- Contabilidad: crear guias de remision desde transferencias internas
- aldelo_connector: filtro de categoria en reporte de ventas por platillo

### Actualizacion 19/12/2023

- Contabilidad: reporte pdf para recibo de ventas

### Actualizacion 26/12/2023

- aldelo: mejoras en log de descuentos para diferenciar descuentos globales por orden

### Actualizacion 06/01/2024

- ecua_analytics_project: agregar ID de sistema externo para evitar duplicados en RRHH

### Actualizacion 09/01/2024

- aldelo: mejoras y correcciones en giftcard
- en reporte de resumen de caja mostrar el valor de venta de certificados
- cuando el uso de certificado se concilie, eso ya no considerarlo en el Saldo por
  conciliar de la caja

### Actualizacion 16/01/2024

- aldelo: Soporte para concepto de Sub recetas
- en reporte de resumen de caja mostrar el valor de certificados conciliados

### Actualizacion 23/01/2024

- aldelo: quitar opcion de eliminar en documentos de restaurante
- contabilidad: correcciones en descuento de NC
- contabilidad: correcciones en retenciones de dividendo

### Actualizacion 30/01/2024

- aldelo: solo validar duplicidad de componentes en subrecetas
- aldelo: mejoras en reportes de aldelo, por impuestos y fechas
- _._: fuente de reportes a 12px

### Actualizacion 06/02/2024

- aldelo: ocultar almacen en transferencias, usar solo ubicaciones
- ecua_utilidades: pasar 1 como parametro a documentos a procesar en lotes
- correcciones en reporte aldelo por hora, usar la fecha de creacion de aldelo

### Actualizacion 20/02/2024

- aldelo: mover boton de conformidad en descuentos para mejor UX
- inventory_counter: pasar la fecha a zona horaria correcta para evitar q se sume 1 dia
  por UTC en el asiento contable
- contabilidad: guardar el total de retencion al descargar el xml

### Actualizacion 27/02/2024

- aldelo: agregar concepto de plantilla en transformacion de productos
- contabilidad: reporte de retencion de ventas en excel
