# ProyectoICC743
Proyecto de la asignatura "Introducción al Análisis de Datos



#Pasos a seguir

#Paso 1
Al descargar el proyecto es necesario crear su propio entorno virtual .venv

##Paso 1.1
Estas son las líneas de código para la creación de un entorno virtual en windows.
python -m venv .venv
.\.venv\Scripts\activate

#Paso 2
Instalar las librerias necesarias para ejecutar el proyecto. Éstas librerias se encuentran en el archivo requirements.txt
Las librerias deben ser instaladas en su propio entorno virtual.

#Paso 3
Crearse una cuenta en kaggle o iniciar sesion en su cuenta.
Dirigirse a settins de su cuenta.
En el apartado donde dice API, solicitar un un nuevo token de acceso.
Este token de acceso será un .json
El archivo .json debe almacenarlo dentro del proyecto en una carpeta llamada .kaggle, su ruta debe ser ./.kaggle

#Paso 4
Direccionar el autenticador de kaggle hacia el archivo .json llamado kaggle.json
Para ello debe crear un archivo .env y colocar la siguiente línea de código
Se redirecciona la busqueda del archivo .json de kaggle para la autenticación

KAGGLE_CONFIG_DIR=./.kaggle

#Paso 5
Si desea subir o actualizar el repositorio es recomendable crear un archivo .gitignore que contenga las siguientes líneas de código

.venv
.env
.kaggle

Listo.

#Paso 6
Utilizar el proyecto.
