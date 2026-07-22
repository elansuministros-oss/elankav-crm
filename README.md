# ELANKAV CRM

Frontend independiente del CRM profesional del ecosistema ELANKAV.

## Arquitectura

```text
ELANKAV CRM (Vite + React)
        ↓
Vercel rewrites
        ↓
ELANKAV Core estable
```

Este repositorio no contiene `api/`, backend propio ni funciones Serverless.

Endpoints consumidos:

- `https://elankav-core.vercel.app/api/auth`
- `https://elankav-core.vercel.app/api/crm`

## Protección

- No modificar producción sin validar Preview.
- No modificar Supabase desde este repositorio.
- No duplicar servicios de ELANKAV Core.

## Validación

La rama `feature/CRM-001-STANDALONE-MIGRATION` es la línea activa de Preview antes de cualquier merge.
