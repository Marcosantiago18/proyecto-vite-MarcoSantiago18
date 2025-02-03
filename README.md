# Descripción del proyecto

## 1. Configuración inicial

En primer lugar he empezado el trabajo creando el nuevo repositorio llamado proyecto-vite-Marcosantiago18 y un direcctorio local para el proyecto

Carpeta del proyecto:

![Captura 1](/images/carpetaProyecto.PNG) 

Como se puede ver en la imagen para crear el directorio local he utilizado los siguientes comandos:

```Bash
    #Creamos la carpeta
    mkdir GitHub_y_Git
    #Nos movemos al directorio
    cd GitHub_y_Git
    #Creamos la carpeta del proyecto
    mkdir proyecto-vite-Marcosantiago18
    #Nos movemos a la carpeta
    cd proyecto-vite-Marcosantiago18
    #Iniciamos el proyecto
    git init
```


Repositorio:

Creamos el repositorio en <a href="https://github.com/" target="_blank">GitHub</a>

![Captura 2](/images/Repositorio.PNG)

Cuando ya tenemos creado el directorio local y el repositorio pasamos a inicializar el proyecto con vite.

![Captura 3](/images/Crearnpm.PNG)

Para inicializar el proyecto he utilizado el siguiente comando: 

```Bash
    npm create vite@lastest
    #Seleccionamos la opcion Vanilla y JavaScripts
    cd proyecto-vite-Marcosantiago18
    npm install
```

![Captura 4](/images/npmInstall.PNG)

Por ultimo, en esta primera parte debemos conectar el directorio local con GitHub con el comando:

```Bash
    git remote add origin git@github.com:Marcosantiago18/proyecto-vite-MarcoSantiago18.git
```

![Captura 5](/images/conectarRepositorio.PNG)

## 2. Trabajo con ramas

#### 1-Crear ramas nuevas
En el primer paso creamos las ramas desarrollo y feature-ui

![Captura 6](/images/Ramas.PNG)

He utilizado los siguientes comandos:

```Bash
    git branch desarrollo
    git branch feature-ui
    #Para ver las ramas creadas
    git branch
```
#### 2-En la rama feature-ui

En segundo lugar modificamos el index.html de la rama feature-ui

HTML:

![Captura 7](/images/ModificacionIndex.png)

En el html he creado un menu con nav donde he añadido una lista con dos elementos uno donde pone inicio que nos dirige al index y otro con un about que nos manda a otro html donde se encuantra el logo de GitHub y si lo pinchas te manda a mi repositorio.

![Captura 8](/images/About.png)


CSS:

![Captura 9](/images/CssModificacion.png)

En el css alineamos el texto al centro y modificamos la lista para que todos los elementos nos salgan seguidos y no le aparezcan los puntos de la lista


#### 3-En la rama desarrollo

## 3. Colaboración

#### 3.1-Propietario del repositorio

En este punto he añadido los colaboradores, pera esto debemos seguir los siguientes pasos:

1. En GitHub, ir a Settings > Collaborators
2. En Manage access > Add people, Bucamos los usuarios
3. Añado el usuario del profesor (isaiasfl)
4. Añado el usuario de un compañero (aormar)

![Captura 10](/images/Invitaciones.png)

#### 3.2-Pasos del Colaborador
1. Aceptar la invitacion de colaboración
![Captura 11](/images/Repositorio_alfonso.png)
2. Clonamos el repositorio
```Bash
    git clone git@github.com:aormar/proyecto-vite-alfonso.git
```
3. Creo la rama Marco en el proyecto 
4. Realizo las siguientes modificaciones:

HTML:
![Captura 12](/images/ModificacionesIndex_Alfonso.png)

En el html he modificado el header añadiendo un h1 y he añadido un botón y le he dado el estilo del siguiente css 

CSS:
![Captura 13](/images/Modificacionccs_Alfonso.png)

6. Subo mi rama al repositorio
```Bash
    git push origin Marco
```
7. Creo el Pull Request
![Captura 14](/images/Pullrequest.png)
![Captura 15](/images/Mergepullrequest.png)
![Captura 16](/images/MergesPullRequest.png)

#### 3.3-Pasos del Propietario


## 4.Integración Final
1. Hago el merge de la rama desarrollo a main
```Bash
    #Estando en la rama main
    git merge desarrollo
```
![Captura 16](/images/Merge_desarrollo.png)


