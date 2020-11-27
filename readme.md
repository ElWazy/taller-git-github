## Conceptos
- Personas dentro de un proyecto
    - La que tiene el codigo
    - La que va a colaborar

![Logo de Git](./img/git_logo.png)

## Inicio de un repositorio(proyecto) con **Git**

#### El que tiene el codigo

```bash
git init
```


#### El que colabora

```bash
git clone [URL_REPO_GITHUB]
```

## Comandos básicos (local)

```bash
git status
git add .
git commit -m "[mensaje]"
```

#### En caso de emergencia

```bash
git checkout [master/main]
```


## Comandos básicos (remoto)

```bash 
git pull --ff
git push origin [master/main]
```


## Ciclo de trabajo (para el que tiene el código)

### La primera vez
```bash
(realiza los cambios con su editor de texto favorito)
git init
git add .
git commit -m "primer commit"

*git remote add origin [url_repo_github]
git branch -M master
git push -u origin master
```

### despues de la primera vez solo hay que repetir
```bash
git pull --ff
(realizar los cambios en su editor de texto favorito)
git status
git add .
git commit -m "[mensaje]"
git push origin [master/main]
```


## Ciclo de trabajo (para el que quiere colaborar)

### La primera vez
```bash
git clone [url_repo_github]
```

### despues de la primera vez solo hay que repetir
```bash
git pull --ff
(realizar los cambios en su editor de texto favorito)
git status
git add .
git commit -m "[mensaje]"
git push origin [master/main]
```
