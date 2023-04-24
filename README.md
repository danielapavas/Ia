# Proyecto Claims Severity Prediction

## Miembros del grupo
* YOHEL OSVALDO PEREZ GARCIA, CC.1035921408, Ingeniería de Sistemas
* TATIANA ELIZABETH SÁNCHEZ SANIN, CC 1125348235, Ingeniería de Sistemas
* DANIELA ANDREA PAVAS BEDOYA, CC 1192741700, Ingeniería de Sistemas


## Datos
Los datos del proyecto se toman de la competición [Allstate State Claims Severity](https://www.kaggle.com/competitions/allstate-claims-severity/data). Los pasos para hacerlos disponibles en google collab son los siguientes:  

1. Estando logueado en la cuenta de Kaggle, irse a Settings y dar click en "Create New Token":  

![image](https://user-images.githubusercontent.com/75345956/233895698-beb81b8b-489c-4bdd-a660-56efc1a1024e.png)

Después de dar click, se descargará un archivo llamado Kaggle.json

2. En el notebook de google Collab ejecutar las siguientes lineas de comando:
```
  !pip install kaggle
  
  from google.colab import files 
  files.upload()
```
Luego dar click en el boton "Elegir archivos" para cargar el archivo .json

![image](https://user-images.githubusercontent.com/55060788/233894298-1c75936e-c9ab-4c9d-8264-da97fa2920e0.png)

3. Por ultimo ejecutar las siguientes lineas de codigo:

```
  ! mkdir ~/.kaggle
  ! cp kaggle.json ~/.kaggle/
  ! chmod 600 ~/.kaggle/kaggle.json
  !kaggle competitions download -c allstate-claims-severity
  !unzip allstate-claims-severity.zip
```


## Videos

- [Video entrega 2](https://youtu.be/wNEXl7stYR4) 
- [Video entrega final]()
