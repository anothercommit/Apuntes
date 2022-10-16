# Ownership

tags: #Apuntes #Progracion #Rust #Concepto

Rust no tiene un garbage collector*, en cambio usa un sistema de ***Ownership*** que son una serie de reglas que de no cumplirse nuestro programa no compilará.

## Reglas:
- Cada valor tiene su *owner*.
- Solo puede haber un *owner* al mismo tiempo.
- Cuando el *owner* se va de scope, es droppeado.