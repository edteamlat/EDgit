# EDgit
Documentación de flujo de trabajo remoto con GIT

## Organización

Se recomienda crear una organización que sea la propitaria del repositorio principal. A partir de dicho repositorio los miembros o colaboradores podrán hacer un fork hacia sus cuentas personales.

### Pasos para crear una organización

1. Click en tu foto perfil (Esquina superior derecha)
2. Click en Settings
3. Click en Organizaciones (Menú izquierdo)
4. Click en Nueva organización
5. Elegir plan y lenar datos

## Creación de Fork

Para crear un fork debes iniciar sesión en GitHub y luego ingresar a la landing page del proyecto del que quieras sacar tu Frok.

## Como trabajar con 2 o más remotos

Listar remotos
`git remote -v`

Agregar remotos
`git remote add EDgit git@github.com:edteamlat/EDgit.git`

Eliminar remotos
`git remote remove EDgit`

## Creando etiquetas

Es necesario entender que las etiquetas (o realeases) sólo deben ser creadas a partir de la rama master como buena práctica. 

Para entender como llamar o categorizar a tus versiones te recomendamos un articulo en nuestro blog: https://ed.team/blog/como-se-deciden-las-versiones-del-software