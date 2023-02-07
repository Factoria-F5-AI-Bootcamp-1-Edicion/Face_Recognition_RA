# Proyecto Computer Vision: CyBees 
Sistema de reconocimiento facial para gestión de entrada.

<h1 align="center">
   <img align="center" width="500" height="500" src="https://user-images.githubusercontent.com/110160219/217216059-5c0c6041-01f5-4c95-9509-7bdb8bc96071.png">
</h1>

# CyBees
Somos el departamento de I.A. de CyBees, una empresa que se dedica de forma inclusiva,  a la consultoría de proyectos tecnológicos. 

Nuestra misión es desarrollar soluciones utilizando algoritmos de IA y Machine Learning para dar respuestas eficientes  a las problematicas que las empresas se enfrentan día a día, así nace CyBee.

# Descripción del proyecto Face Recognition
Nuestra solución dada por nuestro departamento de Inteligencia Artificial de Cybees, propone identificar varias caras de forma simultánea, las personas registradas que podrán entrar al evento están clasificadas, por lo que reconoce la cara, el nombre dado en la lista de invitados y el acceso permitido señalando en nuestro color turquesa corporativo, sin embargo, a las personas no invitadas no les permite el acceso, en color rojo.

Para todo esto disponemos de un ordenador en la puerta del evento en el que con un stream de vídeo marca con "Acceso Permitido" o "Acceso Denegado" para agilizar la entrada y seguir nuestros valores con el medio ambiente.

# :mechanical_arm:Estado del proyecto
:construction: Proyecto en construcción :construction:

*¡Estamos comprometidos a usar la tecnología para facilitar la vida de nuestras clientas!*

<h1 align="center">
   <img align="center" width="1000" height="300" src="https://user-images.githubusercontent.com/110160219/217234309-38f51411-a05c-4abe-b218-df4a8e5c576a.png"
</h1>




## :hammer:Funcionalidades del la solución

- `Funcionalidad 1`: Nuestro algoritmo detecta caras de personas.
- `Funcionalidad 2`: Nuestro algoritmo reconoce la identidad de la persona a través de un vídeo en tiempo real. 
- `Funcionalidad 3`: Nuestro algoritmo nos dice si la persona tiene el permiso o está denegada su entrada.

## 📁 Acceso al proyecto

*Descarga el contenido del repositorio* >> https://github.com/Factoria-F5-AI-Bootcamp-1-Edicion/Face_Recognition_RA.git 

## 🛠️ Abre y ejecuta el proyecto

1. Crea un entorno específicamente para este proyecto. Por ejemplo con conda:
```
conda create -n nombreEntorno (Con esta funcion creas y le das nombre personalizado a tu entorno de trabajo).
```
2. Dentro de este entorno será necesario instalar todas las librerias usadas, lo puedes hacer desde archivo :
```
pip install -r requirements.txt (Con esta función se intala el archivo de requirements.txt)
```

### Quieres reconocer 1 cara, aqui esta el camino: 

- Entra a la carpeta "Primer_Proyecto" y despliega el Notebook.
- Sube la imagen de la cara a reconocer a la capeta "Primer_Proyecto".
- Renombra la imagen con la etiqueta que quieres desplegar en camara.
- Ejecuta el Notebook, se desplegará la camara y reconocera a la persona de la foto. 

### Quieres reconocer varias caras, ve por aqui: 

- Entra a la carpeta "Segundo_Proyecto" y despliega el Notebook llamado "Extracting.ipynb".
- Sube las imagen de las caras a reconocer a la capeta "input_images".
- Ejecuta el "Extracting.ipynb", este reconocera las caras dentro de las fotos y las recorta. Estarán ubicada en la carpeta "faces" que se crea al ejecutar el notebook.
- Al corroborar que estan todas las caras en la carpeta "faces" procedemos a etiquetarlas (Se crearán también falsos positivos, es decir fotos que no son caras y hay que borrarlas).
- Ejecuta el Notebook "Reconocimiento.ipynb" este mismo creara vectores de las caras a reconocer y al finalizar encenderá la camara y reconocerá a las personas de las fotos. 
- Para finalizar/parar el reconocimiento, coloca 1 en video_capture(1).


# Tecnologías usadas:

   - **Metodología Scrum:** Trello (https://trello.com/b/090aa50r/face-recognizer)
   - **Desarrollo en Mac y Windows 10 con:** Git y GitHub, Jupyterlab, Face-Recognition, OpenCv, Os.
   - **Presentación:** Canva (https://www.canva.com/design/DAFZy5Ts9hM/oR2hdznGNoyQmAXOXgdzFw/edit?utm_content=DAFZy5Ts9hM&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) 

# Autoras:


<h1 align="center">
   <img align="center" width="500" height="400" src="https://user-images.githubusercontent.com/110160219/217214395-628db7e0-af18-4575-bf1a-1440e5d9c335.jpg">
</h1>


## :mailbox:Contacta con nosotros:
- Discord Usuarios: *Anitata#2276* & *RebeCas#3477*
- Email: hablanos@cybees.com







