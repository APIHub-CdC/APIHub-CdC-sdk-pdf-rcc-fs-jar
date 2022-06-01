# sdk-pdf-rcc-fs-jar

SDK para generación de PDF para RCC + FicoScore
## Requisitos

1. Java = 1.6

## Ejecución

**Paso 1**: Para ejecutar el archivo **GeneraPDF.jar** es necesario abrir una terminal en la ruta donde se encuentre el archivo **GeneraPDF.jar**.

**Paso 2**: Generar archivo **.txt** con el json de respuesta que corresponde al API Reporte de **Crédito Consolidado + FICO® Score** el cual debe de ir en una sola línea como el archivo **json.txt** que esta en este repositorio.

**Paso 3**: Para generar el PDF se necesita pasar parametros al siguiente comando:


```shell
java -jar {ruta_archivo_jar} {fecha_generacion_pdf} {ruta_pdf_a_crear} {ruta_archivo_json}
```
**Paso 4**: Para realizar una prueba para la generacion del PDF se utilizara el archivo **json.txt** que esta en este repositorio.

**Ejemplo**:
```shell
java -jar GeneraPDF.jar '2022-03-04' '/Users/Documents/PDF_API/pdfCreado.pdf' /Users/Documents/PDF_API/json.txt
```

---
[CONDICIONES DE USO, REPRODUCCIÓN Y DISTRIBUCIÓN](https://github.com/APIHub-CdC/licencias-cdc)

[1]: https://getcomposer.org/doc/00-intro.md#installation-linux-unix-macos