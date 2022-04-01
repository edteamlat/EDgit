# EDgit
Documentación de flujo de trabajo remoto con GIT

## Organización

Se recomienda crear una organización que sea la propietaria del repositorio principal. A partir de dicho repositorio los miembros o colaboradores podrán hacer un fork hacia sus cuentas personales.

### Pasos para crear una organización

1. Click en tu foto perfil (Esquina superior derecha)
2. Click en Settings
3. Click en Organizaciones (Menú izquierdo)
4. Click en Nueva organización
5. Elegir plan y llenar datos

## Creación de Fork

Para crear un fork debes iniciar sesión en GitHub y luego ingresar a la landing page del proyecto del que quieras sacar tu Fork.

### Clon del Fork

Una vez creado el fork, ya podemos empezar a usarlo para añadir cambios en una nueva rama sin el riesgo de afectar el proyecto principal, pero para eso necesitarás descargar tu fork:

```
git clone [link del fork] [opcional:foldername]
# ejemplo
git clone https://github.com/username/EDgit.git "mi carpeta"
git clone https://github.com/username/EDgit.git
```

## Cómo trabajar con dos o más remotos

Agregar remotos

```
git remote add [alias] [repositorio remoto]
# ejemplo
git remote add EDgit git@github.com:edteamlat/EDgit.git
git remote add beto git@github.com:betoquiroga/EDgit.git
```

Listar remotos

```
git remote -v
# output
EDgit   https://github.com/edteamlat/EDgit (fetch)
EDgit   https://github.com/edteamlat/EDgit (push)
...
```

Eliminar remotos

```
git remote remove [alias del repositorio remoto]
# ejemplo
git remote remove EDgit
git remote remove beto
```


## Creando etiquetas

Es necesario entender que las etiquetas (o realeases) sólo deben ser creadas a partir de la rama master como buena práctica. 

Para entender cómo llamar o categorizar a tus versiones te recomendamos un artículo en nuestro blog: [¿Cómo se deciden las versiones de software?](https://ed.team/blog/como-se-deciden-las-versiones-del-software)


### Creacion de  FORK 

Para crear un FORK debes iniciar secion en GitHub y luego ingresar a la LADING page del proyecto del que quieras sacar tu FORK.
