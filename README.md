# Plantilla del Projecte Intermodular de DAW

Repositori base per documentar, planificar, prototipar i validar un projecte en relleu.

## Inici

1. Creeu el repositori del projecte a partir d'esta plantilla.
2. Poseu un identificador estable, el **nom del projecte** i el repositori en [`project.json`](project.json), i actualitzeu [`docs/00-control/projecte.md`](docs/00-control/projecte.md).
3. Cada membre copia [`evidencies/alumnat/plantilla.md`](evidencies/alumnat/plantilla.md) amb el seu nom.
4. En el bloc 1, copieu la [plantilla pública del Dossier 0](https://cipfpbatoi.github.io/pi2627/bloc1-dossier0.html) a `docs/01-proposta/dossier-0.md`.
5. Convertiu este `README.md` en una portada breu que enllace el dossier, els controls i les evidències individuals; no hi copieu tota l'entrega.
6. Creeu una issue per cada tasca abans de començar-la.
7. Treballeu amb branques i *pull requests* revisades.
8. En cada punt de control, creeu una etiqueta i una *release*.

## Qui crea les issues

La plantilla proporciona els formularis, però **cada parella crea les issues concretes**. Definir el resultat, les dependències, els criteris d'acceptació i l'evidència forma part del treball.

En el bloc 1, el professorat pot crear una única issue de posada en marxa. Després, l'equip provisional crea les tasques necessàries per elaborar i revisar el Dossier 0. S'utilitza el mateix procediment en els projectes reals.

## Estructura

```text
docs/00-control/       Identificació, decisions, fonts i IA
docs/01-proposta/      Dossier 0 diagnòstic i Dossier 1 de proposta
docs/02-avantprojecte/ Dossier 2 i dissenys
docs/03-planificacio/  Pla, riscos, cronograma i proves
docs/04-seguiment/     Canvis, incidències i resultats
docs/05-tancament/     Validació, memòria i conclusions
evidencies/alumnat/    Registre individual verificable
prototip/              Codi i instruccions d'execució
traspassos/            Actes entre equips
```

## Primera entrega: Dossier 0

La ubicació canònica és:

```text
project.json
README.md
docs/00-control/projecte.md
docs/00-control/decisions.md
docs/00-control/fonts-ia.md
docs/01-proposta/dossier-0.md
evidencies/alumnat/nom-cognoms.md
```

El dossier conté el treball compartit. Cada reflexió i aportació individual es registra una sola vegada en el fitxer personal i s'enllaça des del dossier i el README. L'etiqueta `dossier-0-v1.0` es crea al final del bloc 1, no després de cada sessió.

Quan comenceu el projecte, substituïu les orientacions inicials d'este README per una portada breu com esta:

```md
# Nom del projecte

## Entrega actual

- [Dossier 0](docs/01-proposta/dossier-0.md)
- [Fonts i ús d'IA](docs/00-control/fonts-ia.md)
- [Decisions](docs/00-control/decisions.md)

## Evidències individuals

- [Nom Cognoms](evidencies/alumnat/nom-cognoms.md)

## Versió entregada

`dossier-0-v1.0`
```

Consulteu [`CONTRIBUTING.md`](CONTRIBUTING.md) abans de treballar.

## Ús d'intel·ligència artificial

Els assistents d'IA han de seguir [`AGENTS.md`](AGENTS.md). La plantilla inclou també instruccions compatibles amb Claude Code, Gemini CLI, GitHub Copilot i Cursor. Estes regles permeten ajuda formativa, però impedixen substituir la reflexió, inventar evidències o redactar l'autoavaluació de l'alumnat.
