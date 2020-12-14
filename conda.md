# ¿Qué es Conda?
Conda es un administrador de paquetes y entornos virtuales para distintos lenguajes de programación.

## Comandos básicos
Para crear un entorno de desarrollo vacío.
```bash
% conda create -n conda-env 
```
Donde "conda-env" es el nombre del entorno que estamos creando. 

💥**Importante:** Este nombre debemos reemplazarlo.

```bash
% conda create -n conda-env python=3.7 
```
Creamos un entorno adaptado a python, es decir, por default se instalan cosas como pip, kernels, etc.
```bash
% conda create -n conda-env numpy=4.2 request=2.1 python=3.8
```
⚠️ **Nota:** Podemos crear el entorno y además, instalar las dependencias que necesitamos. También podemos escoger sus versiones.

Para activar nuestro entorno creado.
```bash
% conda activate conda-env 
(conda-env)%                              #Nuevo Terminal
```

Para desactivar nuestro entorno.

```bash
(conda-env)% conda deactivate    
%                                      #Antiguo Terminal 
```
