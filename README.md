# SchemaSpy - Teradata
SELECT CONCAT('SELECT * FROM ', DatabaseName, '.',TableName,';') FROM "DBC"."TablesV" 
WHERE TableKind = 'T' AND DatabaseName='UNIVERSIDAD' ;

SELECT * FROM UNIVERSIDAD.Profesor;

SELECT * FROM UNIVERSIDAD.Estudiante_Materia;


java -jar schemaspy-6.1.0.jar -configFile config.file -t teradata.properties -vizjs -debug

![image](https://user-images.githubusercontent.com/26145773/154222030-e80abb80-aa1a-4c06-b62a-7a3faea3d703.png)

![image](https://user-images.githubusercontent.com/26145773/154222304-31781bc8-b859-43ce-9ce0-d8e60e9b2051.png)

![image](https://user-images.githubusercontent.com/26145773/154222403-9b1016eb-a593-4fc0-ad59-37c007fcac22.png)
