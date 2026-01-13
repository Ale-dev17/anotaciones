# Instrucciones para el curso
1. Instalacion de Bitwarden en el navegador compatible con Chrome
2. Crearse una cuenta en https://github.com
3. Bajar el instalador de Git, https://git-scm.com/ , el de 64bits, https://github.com/git-for-windows/git/releases/download/v2.52.0.windows.1/Git-2.52.0-64-bit.exe
4. Bajar el instalador de https://notepad-plus-plus.org/
5. Bajar el instalador de [vscode](https://code.visualstudio.com/)


## Para probar
Saber si git se instalo correctamente, se ejecuta los comandos en la powershell `git --version`

### Configurar git local
```
git config --global user.name "nick"
git config --global user.email "tucorreocape@mail.com"
```

### Verificar git local
```
git config user.name
git config user.email
```

### Repos
Crear repositorio: https://github.com/new
preferentemente con el mismo nombre de la carpeta

En la opcion de "Quick setup — if you’ve done this kind of thing before", seleccionar https porfa

Inicializar el repositorio local por primera

```
git init

Initialized empty Git repository in
```

Nos vamos a la pagina de github, en nuestro repositorio que estamos creando, anga
Pegamos esto en la terminal:

```
git remote add origin https://github.com/Ale-dev17/anotaciones.git

```

Para comprobar si realmente pusimos bien el repo de github

```
git remote -v
```

para agregar cambios a git:

```
git add .
```

para confirmar el cambio:

```
git commit -m "mensajito"
```

para enviar al github:
```
git push origin main
```

### Podes instalar en vscode plugins

https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced
