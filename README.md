# Plantilla del Projecte Intermodular de DAW

Repositori base per documentar, planificar, prototipar i validar un projecte en relleu.

## Inici

El professorat crea el repositori de l'equip a partir d'esta plantilla i vos envia una invitació. No creeu un altre repositori ni cloneu el repositori plantilla.

1. Cada membre accepta la invitació de GitHub i obri el repositori assignat dins de `batoi-pi-2026`.
2. Cada membre clona eixe mateix repositori en el seu ordinador:

   ```bash
   git clone https://github.com/batoi-pi-2026/som-barri-equip-01.git
   cd som-barri-equip-01
   git remote -v
   ```

   Substituïu `som-barri-equip-01` pel nom real. `origin` ha d'apuntar al repositori de l'equip, no a `pi2627-plantilla-projecte`.
3. Comproveu la identitat de Git amb `git config user.name` i `git config user.email`. Cada persona ha de treballar amb el seu compte.
4. Creeu o assumiu la issue de posada en marxa. Cada membre obri una branca pròpia, copia [`evidencies/alumnat/plantilla.md`](evidencies/alumnat/plantilla.md) amb un nom de fitxer identificable i publica la branca:

   ```bash
   git switch -c posada-en-marxa/nom-cognoms
   cp evidencies/alumnat/plantilla.md evidencies/alumnat/nom-cognoms.md
   git add evidencies/alumnat/nom-cognoms.md
   git commit -m "docs: crea el registre individual"
   git push -u origin posada-en-marxa/nom-cognoms
   ```

5. Obriu una *pull request* en GitHub. Una altra persona de l'equip la revisa abans d'incorporar-la a `main`. Això comprova el clon, l'autoria, el `push` i la revisió compartida.
6. Abans de cada treball posterior, executeu `git switch main` i `git pull`; després creeu una branca vinculada a la issue corresponent.
7. Reviseu l'identificador, el **nom del projecte** i el repositori de [`project.json`](project.json), i actualitzeu [`docs/00-control/projecte.md`](docs/00-control/projecte.md).
8. En el bloc 1, copieu la [plantilla pública del Dossier 0](https://cipfpbatoi.github.io/pi2627/bloc1-dossier0.html) a `docs/01-proposta/dossier-0.md`.
9. Convertiu este `README.md` en una portada breu que enllace el dossier, els controls i les evidències individuals; no hi copieu tota l'entrega.
10. Creeu una issue per cada tasca, treballeu amb branques i *pull requests* revisades i, en cada punt de control, creeu una etiqueta i una *release*.

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
