# Nombre del proyecto

> Una frase que diga qué hace este proyecto y para quién.

<!-- Insignia de CI (sustituye NOMBRE): [![CI](https://github.com/sastiam/NOMBRE/actions/workflows/ci.yml/badge.svg)](https://github.com/sastiam/NOMBRE/actions/workflows/ci.yml) -->

## Por qué existe
Qué problema resuelve y qué alternativas existen. Sé concreto y honesto: qué hace bien y qué no hace.

## Uso rápido
```bash
# Pasos mínimos y probados para ver el proyecto funcionando
```

## Estado
Pre-1.0 / estable / en pausa (elige uno y mantenlo al día).

## Después de crear un repo desde esta plantilla
GitHub copia los archivos, **no** los ajustes. Falta aplicar la línea base (secret scanning, push protection, CodeQL, ruleset `baseline-main`, borrado automático de ramas):

```bash
apply-baseline.sh settings OWNER/REPO            # simulacro: muestra qué cambiaría
apply-baseline.sh settings OWNER/REPO --apply    # aplica, tras revisar el simulacro
```

El script vive en el vault de Sebastian (`scripts/repo-base/`). Luego sustituye los textos de ejemplo de este README, `dependabot.yml` y `ci.yml`.

## Seguridad
Para reportar una vulnerabilidad, ver [SECURITY.md](SECURITY.md). No abras un issue público.

## Contribuir
Ver [CONTRIBUTING.md](CONTRIBUTING.md).

## Licencia
Ver [LICENSE](LICENSE).
