# Proceso de limpieza de commits

## Pasos realizados

1. Se usó el comando `git rebase -i HEAD~3` para modificar los mensajes de commit.
2. Los commits con mensajes poco claros se cambiaron a:
   - "Arreglos" → "Corregir errores de sintaxis en script.sh"
   - "Cambios" → "Añadir nuevo mensaje a script.sh"
   - "Actualización de cosas" → "Añadir segundo mensaje al script.sh"
3. Finalmente, se realizó un `git push --force` para actualizar el historial en el repositorio remoto.
