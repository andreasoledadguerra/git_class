


### Como empezar?
- Creamos el repo de github con la interfaz web.


##### Clonamos el repositorio.
```bash
git clone https://github.com/andreasoledadguerra/nombe_del_proyecto.git
```

##### Creamos el `.gitignore`.
```bash
# Se elimina siempre el entorno virtual y el __pycache__.
env/
__pycache__/
```

##### Subimos esos cambios al repo.
```bash
git add .gitignore
git commit -m "Se crea .gitignore"
git push
```

##### Creamos el entorno virtual
```bash
python3 -m venv env         # Si ya lo tuviéramos obviamente no volvemos a crear.
source env/bin/activate     # Sabemos que está activado si tiene un (env).

# Y luego instalamos las dependencias del proyecto.
# Generalmente esto se hace con un "requirements.txt".
```


