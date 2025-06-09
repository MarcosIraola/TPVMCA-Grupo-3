# TPVMCA - Grupo 3

## Participantes
- Marcos Iraola
- Gonzalo Corbelli
- Jose Aviles
- Agustin Sanchez

---

## Diagrama de Topología

![Topología](https://marcosiraola.github.io/TPVMCA/TopologiaProyecto.png)

---

### Nota: Directorio `/proc`

Debido a que `/proc` es un sistema de archivos virtual del kernel y no puede ser comprimido completamente (contiene información efímera, cambiante y de solo lectura), se optó por incluir un archivo con su estructura en lugar de comprimir el directorio directamente.

Se encuentra en:
- `proc.txt` → contiene el resultado de `ls -lR /proc` como representación del contenido de `/proc`.
