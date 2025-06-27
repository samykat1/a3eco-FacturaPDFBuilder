# a3eco-FacturaPDFBuilder
Archivo Excel con macros para extraer automáticamente los documentos insertados en el libro de facturas y consolidarlos en un único PDF ordenado según el registro.

✅ Instrucciones de uso
1. Preparación de archivos
Sacar una copia de seguridad de las facturas desde A3ECO.
Copiar la carpeta FACTURAS y el archivo Excel generado en la ruta: \A3\A3ECO\EMP
Luego, pegar esa misma carpeta FACTURAS y el archivo Excel en la carpeta: REQAEAT

2. Generación automática del PDF
Abre el archivo Excel y habilita las macros.
El archivo detectará los documentos insertados (facturas escaneadas) y generará automáticamente un único archivo PDF con todos los documentos ordenados.

🛠 Requiere: PDFtk instalado para combinar los PDFs.



🧭 Uso manual con botones (opcional)
En caso de que haya más de una actividad o prefieras realizar el proceso de forma controlada, puedes usar los 3 botones disponibles en el Excel.
Convertir TIF a PDF: Convierte los archivos escaneados en formato .tif a .pdf.
Reemplazar nombres: Cambia los nombres de los archivos PDF según los datos del libro de facturas.
Combinar PDFs en orden: Une todos los PDFs generados en un único archivo PDF, respetando el orden del libro de facturas.

📌 Para usar esta opción, simplemente cambia los datos en el libro de facturas (según la actividad deseada) y ejecuta los botones en orden.



⚠️ Importante Este Excel está optimizado para empresas con menos de 3.000 facturas, para evitar problemas de rendimiento. Si el número de registros supera los 3.000: Deberás extender manualmente las fórmulas de las columnas N, O y P.
