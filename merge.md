

# Diferencias entre:
# "merge" y "merge--no-ff"

**Apesar de tener un parentesco estos tienen algunas diferencias importantes.**
___


    $ git merge



* Une una o mas ramas en la rama actual en la que estamos posicionados.
* no registra su historia, es decir de donde viene.
* Fusiona de manera rapida las ramas.
___


    $ git merge --no-ff


* Guarda la historia de las ramas.
* Documenta que se hizo merge de otra rama, dejando un rastro y no fusiona de manera rapida.
* Genera un commit para fusionar las dos ramas.
