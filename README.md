# Moises_3Ds_Updates

Moises_3Ds_Updates responde a un proceso de modificación de región en updates, con ello, evitaremos incompatibilidades con la eshop en nuestra consola 3Ds. 
A diferencia de los Juegos, los Updates deben de corresponder a la misma región a la que pertenece nuestra consola, por tanto, no debemos instalar update.cia de región unknow, free o de distinta región a la de nuestra consola. Sin embargo, sí podemos ubicar en su código Todas las Regiones, éste es el objetivo principal del proceso. 

Para la realización de este proceso precisaremos de 3 programas: GodMode9, GabrieloRomToolsGUI y HxD.

1º Paso: Instalar el update en la consola (dará igual su región). No abrir el juego ni entrar a la eshop para evitar baneo.

2º Paso: Abrir GodMode9 (Star+Power con la consola apagada). Acudir al directorio SYSNAND SD y pulsar simultánemente el botón R+A. En la pantalla inferior saldrán una nuevas opciones, seleccionaremos Search for titles. En este nuevo menú aparecerán todos los juegos y updates que hayamos instalado en nuestra consola. Buscaremos el juego que queremos convertir a .cxi. Una vez encontrado, le daremos a la A, TMD file options… , Dump CXI/NDS file. Una vez termine la conversión meteremos la tarjeta Sd en nuestro ordenador. Acudiremos a la Carpeta gm9, a la Carpeta out y ahí estará nuestro juego .cxi. 

3ª Paso: Crear una Nueva Carpeta en el escritorio y meter ahí el archivo .cxi. A continuación, abrir el programa GabrieloRomToolsGUI y acudir a la pestaña Extract NCCH, seleccionar el archivo game.cxi en la primera opción y seleccionar la Nueva Carpeta en la segunda opción. Por último, daremos a Extract! Con ello, obtendremos varios archivos pero el más importante será icon.icn (ubicado en la carpeta exefs).

4º Paso: Abrir el programa HxD y arrastrar el archivo icon.icn. Acudir a la pestaña “Buscar”  y seleccionar la opción “Ir a…”. En “Posición” escribiremos 2018 y le daremos a “Aceptar”. A continuación, modificaremos el serial por: 01 (Japón), 02 (América), 0C (Europea y Australiana) o 0F (Todas las regiones) -se recomienda este último parámetro. Acudiremos a la pestaña “Archivo” y seleccionaremos la opción “Guardar”. Con ello, obtendremos: el archivo icon.icn (el editado) y el archivo icon.icn.bak (deberemos sacarlo de la carpeta exefs o eliminarlo).

5º Paso: Acudir a la pestaña Rebuild NCCH dentro de GabrieloRomToolsGUI. Seleccionar la Nueva Carpeta en la tercera opción y dar a Rebuild. Con ello, obtendremos el archivo edited.cxi. 

6º Paso: Acudir a la pestaña Cia tools y seleccionar la Nueva Carpeta en la primera opción. Acto seguido, presionar el botón Add, escribir edited.cxi y darle a Aceptar. Por último, le daremos a Rebuild! Con ello, obtendremos el archivo example.cia (podéis renombrarlo). 

7º Paso: Comprobar que la región del update.cia es Región Free mediante el uso del FBI. No obstante, podéis reinscribir el ipdate instalado en el 1º Paso o eliminarlo antes de la nueva instalación. 
