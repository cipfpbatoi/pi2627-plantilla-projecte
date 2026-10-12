# Plantilla del Dossier 2. Avantprojecte

Completeu este fitxer a partir de la versió acceptada del Dossier 1 i conserveu l'historial. Enllaceu els diagrames, prototips, proves i fonts; no dupliqueu evidències sense necessitat.

## Com completar l'avantprojecte per sessions

El dossier és acumulatiu. En cada sessió completeu els apartats indicats i reviseu els anteriors quan una prova o una decisió aporte informació nova.

| Moment | Apartats que cal completar o revisar |
| --- | --- |
| Sessió 1. Objectius, èxit i requisits | 1–5; iniciar 12 i registrar l'autoria de la sessió en el 13 |
| Sessió 2. Disseny funcional, dades i arquitectura | 6–7 i 9–10; revisar 5 i ampliar 12–13 |
| Sessió 3. Interfície, viabilitat i traspàs | 8 i 11; completar 12–15 i revisar tot el dossier |

### Checklist concreta de la sessió 1

- **1:** identificació, versió i condicions rebudes del Dossier 1;
- **2:** necessitat, persones i context, indicant només canvis o evidències noves;
- **3:** objectius amb criteris d'èxit observables;
- **4:** abast, exclusions, supòsits i manera de comprovar-los;
- **5:** requisits funcionals i no funcionals prioritzats i verificables;
- **12:** almenys una cadena necessitat → objectiu → requisit → prova;
- **13:** aportacions, autoria, fonts i ús d'IA de la sessió.

No completeu encara el disseny funcional, les dades, la interfície, l'arquitectura, la viabilitat ni el traspàs.

### Checklist concreta de la sessió 2

- **6:** recorregut principal, alternatives, errors i regles funcionals;
- **7:** model i tractament de les dades;
- **9:** arquitectura, integracions i funció dels mínims dels mòduls;
- **10:** alternatives comparades i decisions justificades;
- **5, 12 i 13:** requisits revisats, traçabilitat ampliada i autoria de la sessió.

La guia d'arquitectura i alternatives està integrada en esta sessió; no és una sessió addicional. No tanqueu encara la viabilitat ni la decisió de traspàs.

### Checklist concreta de la sessió 3

- **8:** prototip de baixa fidelitat, prova realitzada i canvis decidits;
- **11:** viabilitat tècnica, temporal, econòmica, legal, operativa i d'ús;
- **12–13:** traçabilitat final, autoria, fonts i ús d'IA;
- **14:** decisió docent, ajustos i acta de traspàs;
- **15:** revisió final completa.

La revisió de viabilitat està integrada en esta sessió. Abans de crear `dossier-2-v1.0`, reviseu també els apartats 1–10 afectats per les proves i decisions.

## 1. Identificació, versions i condicions d'entrada

| Projecte | Equip | Versió i data | Enllaç de treball |
| --- | --- | --- | --- |
|  |  |  |  |

| Condició del bloc 2 | Estat i evidència | Canvi introduït | Responsable |
| --- | --- | --- | --- |
|  |  |  |  |

## 2. Necessitat, persones i context

Resumiu la necessitat validada i enllaceu les fonts del Dossier 1. Indiqueu només els canvis i les evidències noves.

| Persona/rol | Context | Necessitat o barrera | Evidència o hipòtesi | Participació en la validació |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |

## 3. Objectius i criteris d'èxit

| ID | Objectiu | Criteri observable | Mètode i moment | Requisits relacionats |
| --- | --- | --- | --- | --- |
| OBJ-01 |  |  |  |  |

## 4. Abast, exclusions i supòsits

| Inclòs en el prototip | Exclòs o ajornat | Motiu | Condició per revisar-ho |
| --- | --- | --- | --- |
|  |  |  |  |

| Supòsit o dependència | Evidència actual | Impacte si falla | Com i quan es comprovarà |
| --- | --- | --- | --- |
|  |  |  |  |

## 5. Requisits prioritzats

| ID | Requisit verificable | Origen | Prioritat | Criteri/prova | Dependències |
| --- | --- | --- | --- | --- | --- |
|  |  |  |  |  |  |

Incloeu requisits funcionals i no funcionals aplicables.

## 6. Disseny funcional

Enllaceu els fluxos, casos d'ús o històries. Descriviu el recorregut principal, els alternatius, els errors i les regles que no resulten evidents.

| Regla o decisió funcional | Origen | Exemple/cas límit | Requisit afectat |
| --- | --- | --- | --- |
|  |  |  |  |

## 7. Informació i model de dades

Adjunteu el model de les dades pròpies, incloent-hi comptes d'usuari i una entitat del problema. Preveieu migracions, seeders ficticis, validacions i restriccions d'integritat.

| Dada o entitat | Finalitat | Origen | Accés | Conservació | Risc/qualitat |
| --- | --- | --- | --- | --- | --- |
|  |  |  |  |  |  |

## 8. Interfície i prova primerenca

Enllaceu el prototip de baixa fidelitat i documenteu jerarquia, navegació, estats, errors, adaptabilitat i decisions d'accessibilitat.

| Tasca provada | Participant/cas | Observació | Resultat | Canvi o decisió |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |

## 9. Arquitectura i integracions

Adjunteu un diagrama de context o components. Expliqueu l'*stack*, el client, l'autenticació, l'API, el manteniment administratiu, les dades, la integració híbrida, la interfície, la infraestructura en el núvol i la integració i el desplegament continus. Justifiqueu com cada peça complix els [mínims dels mòduls](https://cipfpbatoi.github.io/pi2627/condicions-tecniques.html) i aporta valor al recorregut.

| Component/integració | Necessitat coberta | Responsabilitat | Dependència | Fallada o risc |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |

### Integració dels mínims dels mòduls

Partiu dels [mínims confirmats](https://cipfpbatoi.github.io/pi2627/condicions-tecniques.html). No decidiu ací la qualificació de cada mòdul: expliqueu la funció de cada mínim dins del projecte i com es podrà provar.

| Mòdul | Activitat o mínim | Funció dins del projecte | Requisit, component o pantalla | Prova i evidència prevista | Decisió pendent o risc | Estat |
| --- | --- | --- | --- | --- | --- | --- |
|  |  |  |  |  |  | Confirmat / provisional / pendent |

## 10. Alternatives i decisions

| Decisió | Alternatives | Criteris i evidències | Opció | Conseqüències | Condició de revisió |
| --- | --- | --- | --- | --- | --- |
|  |  |  |  |  |  |

## 11. Viabilitat i riscos

| Dimensió | Evidència/estimació | Límit, cost o recurs | Incertesa/risc | Acció o prova | Conclusió |
| --- | --- | --- | --- | --- | --- |
| Tècnica |  |  |  |  |  |
| Temporal |  |  |  |  |  |
| Econòmica |  |  |  |  |  |
| Legal, dades i permisos |  |  |  |  |  |
| Operació i desplegament |  |  |  |  |  |
| Accessibilitat i ús |  |  |  |  |  |

## 12. Matriu de traçabilitat

| Mòdul/mínim | Necessitat/evidència | Objectiu | Requisit | Component o pantalla | Prova | Risc/decisió |
| --- | --- | --- | --- | --- | --- | --- |
|  |  |  |  |  |  |  |

## 13. Revisió, autoria i ús d'IA

| Aportació o decisió | Autoria/participants | Evidència verificable | Revisió |
| --- | --- | --- | --- |
|  |  |  |  |

| Font o ferramenta d'IA | Finalitat | Ajuda obtinguda | Verificació humana | Canvi resultant |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |

Cada membre adjuntarà la seua defensa d'una cadena de traçabilitat i d'una decisió, incloent-hi objeccions o canvis de criteri.

## 14. Decisió docent i traspàs al bloc 4

| Resultat | Data | Condicions | Persona que valida |
| --- | --- | --- | --- |
| Apta per planificar / apta amb ajustos / revisar |  |  |  |

| Ajust | Responsable | Evidència | Data | Estat |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |

### Acta de traspàs

| Dada | Registre |
| --- | --- |
| Versió entregada i data |  |
| Parella autora/emissora |  |
| Parella planificadora/receptora |  |
| Evidències i recursos accessibles |  |
| Qüestions obertes i riscos coneguts |  |
| Acceptat / amb reserves / retornat |  |
| Reserves o elements per completar |  |

| Pregunta del receptor | Resposta de l'autor | Evidència o decisió afectada | Data |
| --- | --- | --- | --- |
|  |  |  |  |

## 15. Revisió final

- [ ] Els objectius i requisits deriven d'evidències o hipòtesis identificades.
- [ ] El recorregut principal, els errors i les exclusions són coherents.
- [ ] Les dades recollides són necessàries i tenen accés i conservació definits.
- [ ] El prototip s'ha contrastat i els canvis estan registrats.
- [ ] L'arquitectura no conté components sense justificació.
- [ ] Les alternatives i els riscos tenen evidències o proves.
- [ ] La viabilitat considera temps, recursos, costos, dades, permisos i desplegament.
- [ ] Cada mínim confirmat dels mòduls té una funció real dins del projecte i requisits, riscos, proves i evidències previstos.
- [ ] La matriu permet seguir una cadena completa fins a la prova.
- [ ] L'autoria, les fonts i l'ús d'IA són identificables.

## Abast curricular de l'evidència

El dossier pot aportar evidència **suficient dins del bloc** de RA2.a, RA2.c, RA2.d, RA2.h i RA2.i si el contingut és coherent i verificable. Aporta evidència **parcial** de RA2.b, RA2.e, RA2.f i RA2.g, que s'ampliarà amb la planificació i l'execució. L'abast real s'ha de determinar per alumne o alumna a partir de les aportacions i la defensa.
