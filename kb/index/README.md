# Índice de la Base de Conocimiento

Este directorio contiene los índices maestros de todos los registros de la KB.

## Archivos de Índice

| Archivo | Contenido |
|---------|-----------|
| `incidencias.md` | Catálogo de todas las incidencias registradas |
| `soluciones.md`  | Catálogo de todas las soluciones registradas |
| `scripts.md`     | Catálogo de todos los scripts registrados |

## Formato de Entrada

Cada índice usa el siguiente formato de tabla:

```markdown
| ID | Título | Servicio | Estado | Fecha | Relacionados |
|----|--------|----------|--------|-------|--------------|
```

## Mantenimiento

- Los índices se actualizan automáticamente cada vez que el agente crea o modifica un registro.
- Los enlaces cruzados entre INC ↔ SOL ↔ SCR se mantienen consistentes.
- No editar manualmente estos archivos; usar el agente para garantizar consistencia.
