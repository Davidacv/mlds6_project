# Análisis exploratorio de datos 

Este documento contiene los resultados del análisis exploratorio de datos.

## Exploración temprana de datos y control de calidad de datos

En este paso se procede a mirar la calidad de los datos. Muchas de las columnas son variables númericas excepto Category y Sex. También es posible ver que hay datos que pueden ser limpiados como es el caso de los datos faltantes.
## Estructura de los datos
![info](https://user-images.githubusercontent.com/85200382/207717776-a25edaee-04bc-457c-906b-49145b508162.png)

Los datos recopilados consta de 13 variables relacionadas con los test hechos sobre las muestras de sangre. En total se tienen 615 entradas para cada variable sin embargo hay datos faltantes
La descripción de cada columna se da a continuación:

*   **Category**: Define el tipo de paciente 0=Donante de sangre', '0s=Donante de sangre sospechoso', '1=Hepatitis', '2=Fibrosis', '3=Cirrosis'
*   **Age**: Define la edad del paciente
*   **Sex**: Define el sexo biológico del paciente
*   **ALB**: Define los niveles de albúmina en la sangre. La albúmina es una proteína producida por el hígado. El examen de albúmina en suero mide la cantidad de esta proteína en la parte líquida y transparente de la sangre.
*   **ALP**: Define los niveles de fosfatasa alcalina en la sangre. Niveles anormales de fosfatasa alcalina en la sangre pueden ser un signo de un gran número de afecciones de salud, incluyendo enfermedad hepática, trastornos de los huesos y enfermedad renal crónica. 
*   **ALT**: ALT significa alanina aminotransferasa. Es una enzima que se encuentra principalmente en el hígado. Una prueba de ALT mide la cantidad de ALT en la sangre. La prueba de sangre de ALT es parte de una prueba sanguínea de rutina para revisar la salud del hígado. La prueba también permite diagnosticar y monitorear problemas del hígado.
*   **AST**: La AST (aspartato aminotransferasa) es una enzima que se encuentra principalmente en el hígado, pero también está en los músculos. Cuando las células que contienen AST están dañadas, liberan el AST en su torrente sanguíneo. La prueba de sangre de AST mide la cantidad de AST en la sangre. En general, esta prueba se usa para diagnosticar daño o enfermedad del hígado (hepática).
*   **BIL**: Mide los niveles de bilirrubina en la sangre. La bilirrubina es una sustancia amarillenta que se forma durante el proceso normal de descomposición de los glóbulos rojos viejos por el cuerpo. La bilirrubina se encuentra en la bilis, un líquido segregado por el hígado que ayuda a digerir los alimentos. El examen de bilirrubina en sangre se usa para examinar la salud del hígado. 
*   **CHE**:  Mide los niveles de 2 sustancias que ayudan al sistema nervioso a funcionar apropiadamente. Dichas sustancias se llaman acetilcolinesterasa y seudocolinesterasa. Los nervios necesitan estas sustancias para enviar señales.
*   **CHOL**: Mide los niveles de colesterol y brinda información importante sobre el riesgo de desarrollar enfermedades cardiacas. 
*   **CREA**:  Mide los niveles de creatinina en la sangre o en la orina. La creatinina es un producto de desecho generado por los músculos como parte de la actividad diaria. Normalmente, los riñones filtran la creatinina de la sangre y la expulsan del cuerpo por la orina. Cuando hay un problema con los riñones, la creatinina se puede acumular en la sangre y sale menos por la orina. Los niveles anormales de creatinina en la sangre o en la orina pueden ser signo de enfermedad renal.
*   **GGT**: La prueba de la gamma-glutamil transferasa (también conocida como gama-glutamiltransferasa o GGT) mide la cantidad de GGT en la sangre. La GGT es una enzima que está en todo el cuerpo, principalmente en el hígado. Cuando el hígado está dañado, la GGT se puede filtrar a la sangre. Los niveles altos de GGT en la sangre pueden ser un signo de enfermedad del hígado o de daño en las vías biliares. Las vías biliares son los conductos por donde la bilis entra y sale del hígado. La bilis es un líquido producido por el hígado. Juega un papel importante en la digestión.
*   **PROT**: Mide la cantidad total de dos clases de proteínas encontradas en la porción líquida de la sangre: albúmina y globulina.
Las proteínas son partes importantes de todas las células y tejidos.
La albúmina ayuda a impedir que se escape líquido de los vasos sanguíneos. También transporta químicos a través de su sangre.
Las globulinas son una parte importante del sistema inmunitario.

## Estadisticas de las variables númericas

![describe](https://user-images.githubusercontent.com/85200382/207717821-522c2294-7564-43d7-816b-8f183794a03d.png)

![displot_barplot](https://user-images.githubusercontent.com/85200382/207718043-34a19813-8996-45a1-84ef-634b13b20043.png)

## Distribución de la variable category

![labels](https://user-images.githubusercontent.com/85200382/207718022-4cb0be90-14e9-4faf-8078-b82bcafcd1d6.png)

Se observa que en este dataset los pacientes con afecciones detectadas representa alrededor del 15% del total de pacientes.
Tambien es claro que existen datos faltantes los cuales pueden ser eliminados.
