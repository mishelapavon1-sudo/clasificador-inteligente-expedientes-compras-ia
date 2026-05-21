# clasificador-inteligente-expedientes-compras-ia
Flujo de Microsoft Power Automate con AI Builder para validación inteligente de expedientes y procesamiento automático de documentos.

# Descripción general

Este proyecto contiene la exportación de un flujo de Microsoft Power Automate denominado **“FLUJO PROYECTO CLASIFICADOR INTELIGENTE DE EXPEDIENTES”**.

El flujo automatiza el procesamiento documental mediante dos etapas principales:

1. Clasificación inteligente de documentos utilizando AI Builder.
2. Validación automática de expedientes mediante lógica documental en Power Automate.

La solución permite:

- Procesar documentos automáticamente.
- Clasificar archivos mediante inteligencia artificial.
- Recorrer carpetas SharePoint.
- Comparar documentos contra listas de control.
- Detectar documentos faltantes.
- Validar integridad documental.
- Registrar resultados automáticamente.

# Funcionamiento general del flujo

## Etapa 1 – Clasificación documental con IA

El flujo utiliza AI Builder para:

- Analizar documentos.
- Identificar tipos documentales.
- Clasificar archivos automáticamente.
- Obtener niveles de confianza.
- Procesar documentos digitalizados.

### Servicios utilizados

- AI Builder
- Power Automate
- SharePoint Online



## Etapa 2 – Validación automática del expediente

Una vez clasificados los documentos, Power Automate ejecuta validaciones automáticas mediante:

- Comparación de listas SharePoint.
- Verificación de carpetas documentales requeridas por cada tipo de compra. 
- Conteo de archivos encontrados.
- Comparación entre documentos esperados y existentes.
- Validación de estructura documental.
- Registro automático de inconsistencias.

La validación final del expediente se realiza mediante lógica automatizada y no exclusivamente por IA.

# Arquitectura de la solución

| Componente | Función |
|---|---|
| Microsoft Forms | Captura de información |
| Power Automate | Automatización y validaciones |
| SharePoint Online | Repositorio documental |
| Power Apps | AI Builder |
| AI Builder | Clasificación documental inteligente |

# Validaciones realizadas

| Validación | Descripción |
|---|---|
| Clasificación IA | Identificación automática documental |
| Conteo documental | Verificación de cantidad de archivos |
| Comparación de listas | Validación contra registros SharePoint |
| Verificación de carpetas | Validación estructural |
| Detección de faltantes | Identificación de documentos ausentes |
| Validación de expedientes | Integridad documental completa |

---

# Resultado final

El flujo genera automáticamente:

- Estado del expediente.
- Documentos faltantes.
- Resultados de validación.
- Clasificación documental.
- Reportes automáticos.
- Registro centralizado en SharePoint.
