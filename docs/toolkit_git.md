#### Primeros pasos haciendo uso de git

Lo primero que tenemos que hacer es como podemos inicializar un proyecto y esto lo hacemos como:
```git
git init
```

Luego podemos ver el estado actual del repositorio:
```git
git status
```

Cuando ejecutamos el comando anterior podemos ver en rojo todos los ficheros o directorios que no estan comprometos por el repositorio en la etapa de stage. Para agregarlos lo podemos hacer con:
```git
git add readme.md
```

Luego una vez que nosotros agregamos un archivo dentro de la etapa de stage podemos comprometer nuestros archivos a la etapa de commit:
```git
git commit -m "Comentario"
```

Para nosotros poder crear un repositorio lo que tenemos que hacer es ir a github y crear el repositorio manual. Una vez creado tenemos que copiar la siguiente sentencia en el repositorio donde estamos trabajando para que se sincronicen. Luego lo que hacemos es pushear los cambios comiteados a la rama donde estas trabajado en el repo. En este caso:
```git
git remote add origin https://github.com/LautaroPintos/finance_fundamentals.git
git push -u origin main
```


