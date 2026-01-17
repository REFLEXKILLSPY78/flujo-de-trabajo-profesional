## Workflow

- `main`: producción (protegida)
- `juan`: producción de juan
- `perez`: producción de perez
- `develop`: integración
- `feature/*`: nuevas funcionalidades
- `hotfix/*`: errores críticos

### Reglas
- ❌ No push directo a main
- ✅ Todo entra por Pull Request
- ✅ CI obligatorio
- ✅ 1–2 aprobaciones mínimas
- ❌ No rebase en ramas compartidas
