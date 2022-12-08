# Git
El git es un control de versiones, el cual nos permite almacenar etapas de nuestro desarrollo, para en cierto momento poder rescatarlas.

## Como almacenar versiones en git.

Primero tenemos que poner nuestro codigo en el modo stage, es una fase previa para que podamos checar lo que queremos almacenar.

```bash
$> git add <filename>
```

si quieres almacenar todos los ficheros puedes usar el comando:

```bash
$> git add .
```
o

```bash
$> git add -A
```

Puedes ver como está el stage con el comando:
```bash
$> git status
```

Una vez tengamos los cambios que queremos almacenar ejecutamos el comando:
```bash
$> git commit -m "mensaje"
```
y te genera el snapshot. Que puedes ver con el comando:

```bash
$> git log
```

Para sincronizar la rama local con la rama remota usamos 2 comandos: <br>
Este comando empuja los commits locales a la nube.

```bash
$> git push
```
Este comando trae los commits remotos a tu local.
```bash
$> git pull
```