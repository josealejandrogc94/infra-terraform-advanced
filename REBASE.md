# REBASE.md

## Objetivo
Reescribir el historial de Git para mejorar la claridad de los mensajes de commit y fusionar commits innecesarios.

## Pasos realizados

1. **Creación de commits originales con mensajes poco claros**  
   - `fix`  
   - `update`  
   - `stuff`

2. **Rebase interactivo**  
   Ejecuté:
   ```bash
   git rebase -i HEAD~3
