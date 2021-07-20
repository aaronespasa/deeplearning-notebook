# Aprende Deep Learning

# Configuración inicial
Para utilizar los notebooks, necesitarás un ordenador con [Anaconda](https://docs.anaconda.com/anaconda/install/) instalado y tendrás que instalar los paquetes necesarios.

## Descarga el repositorio
Clona el repositorio utilizando HTTPS:
```bash
$ git clone https://github.com/aaronespasa/Deep-Learning-Pytorch-es.git
```

## Activa el environment del repositorio
Primero debes crear el environment en tu ordenador:
```bash
$ conda env create -f environment.yml
```

Una vez lo ejecutes, te instalará todos los paquetes necesarios en un environment llamado `dl-env`.
Para activar este environment:
```bash
$ conda activate dl-env
```

# Abre el repositorio con Jupyter
Recomiendo utilizar Jupyter Lab ya que nos proporciona una interfaz que nos permite abrir varias terminales y notebooks en una misma pestaña.
Para eso, ejecutamos el siguiente comando en la terminal (con `dl-env` activado):
```bash
$ jupyter lab
```

