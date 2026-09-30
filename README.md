# Plantilla del Projecte Intermodular de DAW

Repositori base per documentar, planificar, prototipar i validar un projecte en relleu.

## Ritme del projecte

Després del Bloc 1, el recorregut prioritza el prototip: Bloc 2 (6 h, proposta), Bloc 3 (9 h, avantprojecte i prova tècnica reduïda), Bloc 4 (9 h, pla mínim executable i traspàs), Bloc 5 (57 h, prototip i validació) i Bloc 6 (9 h, tancament). Manteniu un únic fil de traçabilitat entre necessitat, requisit, issue, prova, resultat i decisió; no dupliqueu esta informació en documents diferents.

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

5. Obriu una *pull request* en GitHub amb `Relacionada amb #1`, sense usar `Tanca #1`. Una altra persona de l'equip la revisa abans d'incorporar-la a `main`; la issue compartida es tanca manualment quan totes les persones acaben. Això comprova el clon, l'autoria, el `push` i la revisió compartida.
6. Abans de cada treball posterior, executeu `git switch main` i `git pull`; després creeu una branca vinculada a la issue corresponent.
7. Reviseu l'identificador, el **nom del projecte** i el repositori de [`project.json`](project.json), i actualitzeu [`docs/00-control/projecte.md`](docs/00-control/projecte.md).
8. Comenceu el treball definitiu amb `docs/01-proposta/dossier-1.md`, que ja incorpora la plantilla de la proposta. No creeu còpies paral·leles ni traslladeu ací el Dossier 0 del Bloc 1.
9. Convertiu este `README.md` en una portada breu que enllace el dossier, els controls i les evidències individuals; no hi copieu tota l'entrega.
10. Creeu una issue per cada tasca, treballeu amb branques i *pull requests* revisades i, en cada punt de control, creeu una etiqueta i una *release*.

## Qui crea les issues

La plantilla proporciona els formularis, però **cada equip crea les issues concretes**. Definir el resultat, les dependències, els criteris d'acceptació i l'evidència forma part del treball.

En els projectes definitius, l'equip crea les issues concretes a partir del Dossier 1, el Dossier 2 o el Pla que tinga en custòdia. No convertiu les seccions d'una plantilla en issues automàtiques: formuleu un resultat, dependències, criteri d'acceptació i evidència adequats.

## Estructura

```text
docs/00-control/       Identificació, decisions, fonts i IA
docs/01-proposta/      Dossier 1 de proposta
docs/02-avantprojecte/ Dossier 2 i dissenys
docs/03-planificacio/  Pla, riscos, cronograma i proves
docs/04-seguiment/     Canvis, incidències i resultats
docs/05-tancament/     Validació, memòria i conclusions
evidencies/alumnat/    Registre individual verificable
prototip/              Codi i instruccions d'execució
traspassos/            Actes entre equips
```

## Primera entrega definitiva: Dossier 1

La ubicació canònica és:

```text
project.json
README.md
docs/00-control/projecte.md
docs/00-control/decisions.md
docs/00-control/fonts-ia.md
docs/01-proposta/dossier-1.md
evidencies/alumnat/nom-cognoms.md
```

El dossier conté el treball compartit. Cada reflexió i aportació individual es registra una sola vegada en el fitxer personal i s'enllaça des del dossier i el README. L'etiqueta `dossier-1-v1.0` es crea al final del bloc 2.

Quan comenceu el projecte, substituïu les orientacions inicials d'este README per una portada breu com esta:

```md
# Nom del projecte

## Entrega actual

- [Dossier 1](docs/01-proposta/dossier-1.md)
- [Fonts i ús d'IA](docs/00-control/fonts-ia.md)
- [Decisions](docs/00-control/decisions.md)

## Evidències individuals

- [Nom Cognoms](evidencies/alumnat/nom-cognoms.md)

## Versió entregada

`dossier-1-v1.0`
```

Consulteu [`CONTRIBUTING.md`](CONTRIBUTING.md) abans de treballar.

## Ús d'intel·ligència artificial

Els assistents d'IA han de seguir [`AGENTS.md`](AGENTS.md). La plantilla inclou també instruccions compatibles amb Claude Code, Gemini CLI, GitHub Copilot i Cursor. Estes regles permeten ajuda formativa, però impedixen substituir la reflexió, inventar evidències o redactar l'autoavaluació de l'alumnat.
