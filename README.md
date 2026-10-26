# Intérêts moratoires – id est avocats

*English version below.*

Outil en ligne de calcul des intérêts moratoires en droit suisse, développé par id est avocats Sàrl. Interface en français et en anglais.

> **Aide au calcul uniquement.** Le résultat doit toujours être vérifié par l’utilisateur. Voir [AVERTISSEMENT.md](AVERTISSEMENT.md).

Version 1.0 (beta), octobre 2026. Historique : [CHANGELOG.md](CHANGELOG.md).

## Ce que fait l’outil

- Calcul des intérêts moratoires sur une ou plusieurs créances, chacune avec son montant, la date dès laquelle les intérêts courent, son taux (5 % par défaut, art. 104 al. 1 CO) et, si nécessaire, sa propre date de fin.
- Imputation des acomptes d’abord sur les intérêts échus, puis sur le capital (art. 85 al. 1 CO), sans intérêts sur les intérêts (art. 105 al. 3 CO).
- Méthode par défaut : jours calendaires sur 365, du jour de départ inclus au jour d’arrêt exclu, total arrondi aux 5 centimes. Une rubrique de variantes permet de choisir la méthode 30/360 européenne (notamment utilisée par l’Office des poursuites de Genève) ou les jours calendaires sur 360, de compter le dernier jour et de renoncer à l’arrondi.
- Trois textes prêts à copier : positions pour une réquisition de poursuite, conclusions d’une demande, décompte chiffré.
- Alertes en cas de taux inférieur à 5 % (art. 104 al. 1 CO), de taux supérieur (art. 104 al. 2 et 3 CO) ou de dates incohérentes.

## Utilisation

1. Indiquer la date à laquelle le décompte est arrêté et, si nécessaire, le taux par défaut.
2. Saisir chaque créance : titre ou cause, montant, date de départ des intérêts, taux. Le taux de chaque créance reprend le taux par défaut (affiché en grisé) tant qu’il n’est pas modifié.
3. Ajouter les acomptes éventuels et choisir la créance sur laquelle chacun est imputé (art. 86 et 87 CO en cas de pluralité de dettes).
4. Si nécessaire, choisir une autre méthode de calcul dans la rubrique « Variante de méthode de calcul ».
5. Copier le texte utile : réquisition de poursuite, conclusions ou décompte.

La langue se choisit en haut de la page (FR / EN) ; l’adresse `?lang=en` ouvre directement la version anglaise. L’affichage peut être réglé en mode clair, sombre ou automatique.

## Protection des données

id est avocats ne collecte aucune donnée dans le cadre de l’utilisation de l’outil : les calculs sont effectués dans le navigateur et les montants saisis ne sont pas conservés. Seuls le mode d’affichage et la langue sont mémorisés dans le stockage local du navigateur (clés `idest-interets:theme` et `idest-interets:lang`). L’outil est hébergé sur GitHub, qui peut collecter certaines informations, notamment au moyen de cookies, conformément à sa propre déclaration relative à la protection des données.

## Sources et tests

- Bases légales et références : [SOURCES.md](SOURCES.md).
- Cas de référence à refaire après chaque modification : [CAS-DE-TEST.md](CAS-DE-TEST.md).

## Licence

© 2026 id est avocats Sàrl.

Le code est distribué sous licence GNU Affero General Public License, version 3 ou toute version ultérieure (AGPL-3.0-or-later). Voir [LICENSE](LICENSE).

Les tableaux et textes juridiques (principes juridiques, textes générés, documentation) sont en outre mis à disposition sous licence [Creative Commons Attribution – Pas d’utilisation commerciale 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.fr). Attribution : « id est avocats Sàrl, Intérêts moratoires ».

---

# Default interest – id est avocats (English)

Online tool for calculating default interest under Swiss law, developed by id est avocats Sàrl. Interface in French and English.

> **Calculation aid only.** Users must always check the result themselves. See the [disclaimer](AVERTISSEMENT.md#disclaimer-english).

## What the tool does

- Calculates default interest on one or more claims, each with its amount, the date from which interest runs, its rate (5% by default, Art. 104 para. 1 CO) and, if needed, its own end date.
- Applies part payments first to accrued interest, then to the principal (Art. 85 para. 1 CO), with no interest on interest (Art. 105 para. 3 CO).
- Default method: calendar days over 365, last day not counted, total rounded to 5 centimes; variants: 30/360 European method (used in particular by the Geneva Debt Enforcement Office) and calendar days over 360.
- Three texts ready to copy: items for a debt collection request, prayers for relief, interest statement. Debt collection requests and court submissions must be filed in the official language of the authority; the English texts are for reference only.

## Data protection

id est avocats does not collect any data through the use of the tool: calculations are performed in the browser and the amounts entered are not stored. Only the display mode and language are stored in the browser’s local storage. The tool is hosted on GitHub, which may collect certain information, including by means of cookies, in accordance with its own privacy statement.

## Licence

© 2026 id est avocats Sàrl. Code licensed under the GNU AGPL 3.0 or any later version (see [LICENSE](LICENSE)); legal tables and texts also available under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). Attribution: “id est avocats Sàrl, Default interest”.
