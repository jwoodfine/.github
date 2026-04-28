---
title: Jennifer Woodfine — Perfil de GitHub
audience: identity-passport
last_edited: 2026-04-28
lang: es
---

# Jennifer Woodfine

Soy empleada de Woodfine Management Corp., empresa que actúa como
Cliente de PointSav Digital Systems en nuestro flujo de desarrollo.

PointSav (el Proveedor) mantiene la fuente de ingeniería canónica del
substrato tecnológico. Woodfine Management Corp. (el Cliente) opera el
despliegue descendente y devuelve contribuciones de código al Proveedor
a través de un nivel intermedio de preparación, donde Peter Woodfine y
yo alternamos la autoría de los commits.

## Qué confirma esta cuenta

Esta cuenta es la identidad de nivel de preparación para los commits de
Jennifer Woodfine en el flujo de desarrollo del substrato. Cada commit
firmado como `jwoodfine` lleva mi clave SSH y se registra primero en el
espejo de esta cuenta, antes de ser promovido a la fuente canónica del
Proveedor.

El substrato al que contribuyo es Foundry: un substrato de contenido,
inferencia y redacción por tenant que PointSav opera como Proveedor y
que Woodfine Management Corp. consume como primer Cliente.

## Cómo funciona el flujo de contribución

Las contribuciones al substrato Foundry siguen este recorrido:

1. Se crean localmente en la VM compartida mediante la herramienta de
   commit de nivel de preparación, alternando identidad entre Jennifer
   y Peter.
2. Se publican en el espejo de nivel de preparación (esta cuenta).
3. Se promueven a la fuente de ingeniería canónica del Proveedor
   (`github.com/pointsav/<repo>`), actualmente mediante script local;
   previsto migrar a GitHub Actions cuando el número de contribuidores
   lo justifique.

Los contribuidores externos no abren pull requests directamente en esta
cuenta. El flujo de contribución pasa por los repositorios canónicos del
Proveedor.

## Consultar también

- `github.com/pointsav` — Fuente canónica de ingeniería del Proveedor
- `github.com/woodfine` — Organización del Cliente; despliegue
  descendente
- `github.com/pwoodfine` — Peter Woodfine, compañero contribuidor de
  nivel de preparación
