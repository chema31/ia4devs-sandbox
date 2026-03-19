# CLAUDE.md — ia4devs-sandbox

## Proyecto
Demo del Master **IA4Devs**. Aplicaciones web con IA + agentes y automatización.

## Stack
- **Runtime / PM**: Bun (`bun add`, `bun run`)
- **Lenguajes**: JavaScript + TypeScript
- **Repo**: github.com/chema31/ia4devs-sandbox

## Metodología: Spec-Driven Development
1. Toda feature nueva empieza con un spec en `specs/<feature>.md`
2. El spec debe estar en estado `approved` antes de escribir código
3. Las PRs referencian su spec: `Implements: specs/<feature>.md`

## Convenciones
- Código e identificadores en inglés
- Commits en inglés (estilo imperativo: `Add`, `Fix`, `Update`)
- Conversaciones con el usuario en español
- No hacer commits automáticos sin confirmación explícita
- No push sin confirmación explícita

## Estructura del repositorio
```
specs/          # Especificaciones de features
src/            # Código fuente
CLAUDE.md       # Este fichero
```

## Sesión con Claude Code
claude --resume a196a19a-6f4a-4115-91a5-496e55057686