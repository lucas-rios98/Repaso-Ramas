# Clase o6 - Bootcamp

## Repaso git

# Creo el repositorio de git

```sh
git status
```

# Haciendo un commit 

1. Agrego al staging area los archivos que necesito que formen parte del commit

```sh
git add  (nombre-archivo)
git add  (nombre-archivo) (nombre-archivo) (nombre-archivo)
git add .  # agrega todos los archivos que tengo en el working directort (WD)

2.Hago el commit

```sh
git config --global core.editor nano
git config --global core editor "code --wait"
```

# Agregar un remoto a mi repositorio local

```sh
git remote add origin https://github.com/lucas-rios98/Repaso-Ramas.git
```

# Para ver si se agrego el remoto

```sh
git remove -v
```

# Subo el remoto al repositorio local

```sh
git push -u Origin # la primera vez
git push
```

# para recuperar mi codigo luego de una catastrofe
ir  al repositorio de GitHub, hacer click sobre el boton de code  y copiar la url a mi repositorio
```sh
git clone  (url-al-repositorio)
git clone  https://github.com/lucas-rios98/Repaso-Ramas.git ./ # clona en el directorio actual
git clone https://github.com/lucas-rios98/Repaso-Ramas.git #  crea una carpeta (repaso ramas )y clona  el repositorio remoto en local


agrego texto

