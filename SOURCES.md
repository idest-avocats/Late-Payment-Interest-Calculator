# Sources

© 2026 id est avocats Sàrl ; textes sous licence [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.fr). Version 1.0 (beta).

Textes consultés sur Fedlex, Code des obligations (CO, RS 220), état au 1er octobre 2026. Une consolidation du CO est annoncée au 1er juillet 2027 : vérifier qu’elle ne touche pas les dispositions ci-dessous.

| Disposition | Contenu | Utilisation dans l’outil |
|---|---|---|
| [Art. 85 CO](https://www.fedlex.admin.ch/eli/cc/27/317_321_377/fr#art_85) | Un paiement partiel ne s’impute sur le capital que si le débiteur n’est pas en retard pour les intérêts ou les frais. | Imputation des acomptes d’abord sur les intérêts échus, puis sur le capital. |
| [Art. 86 et 87 CO](https://www.fedlex.admin.ch/eli/cc/27/317_321_377/fr#art_86) | Imputation en cas de pluralité de dettes (déclaration du débiteur, quittance, dette échue la première). | L’utilisateur choisit la créance sur laquelle chaque acompte est imputé. |
| [Art. 102 CO](https://www.fedlex.admin.ch/eli/cc/27/317_321_377/fr#art_102) | Demeure par interpellation (al. 1) ou à l’expiration d’un terme fixé (al. 2). | Rappel sur le point de départ des intérêts (date saisie par l’utilisateur). |
| [Art. 104 CO](https://www.fedlex.admin.ch/eli/cc/27/317_321_377/fr#art_104) | Intérêt moratoire de 5 % l’an (al. 1) ; taux conventionnel supérieur (al. 2) ; taux de l’escompte entre commerçants (al. 3). | Taux par défaut de 5 % ; alertes pour un taux inférieur ou supérieur. |
| [Art. 105 CO](https://www.fedlex.admin.ch/eli/cc/27/317_321_377/fr#art_105) | Intérêts, arrérages et donations : intérêt moratoire dès la poursuite ou la demande (al. 1) ; pas d’intérêts sur les intérêts moratoires (al. 3). | Intérêts échus impayés présentés comme une créance distincte sans intérêts. |

Version anglaise des dispositions : [Fedlex, CO en anglais](https://www.fedlex.admin.ch/eli/cc/27/317_321_377/en). La traduction anglaise n’a pas de valeur légale.

## Choix de calcul

- Méthode par défaut : jours calendaires sur 365, jour d’arrêt non compté, total arrondi aux 5 centimes. Variantes : « 30/360, méthode européenne », qui compte chaque mois pour 30 jours (les 31 comptent comme 30), comme la fonction Excel JOURS360 avec la méthode européenne ; « jours calendaires sur 360 », qui compte les mêmes jours que la méthode par défaut mais divise par 360.
- Office des poursuites de Genève, « Aide au calcul des intérêts » (fichier Excel destiné aux productions de créances dans la faillite) : intérêts = capital × taux × JOURS360(date de début ; date de fin ; méthode européenne) ÷ 360, total arrondi aux 5 centimes, jour de fin non compté. La variante « 30/360, méthode européenne » reproduit ce calcul ; un écart d’au plus 5 centimes par créance peut subsister, l’Office arrondissant chaque ligne et l’outil le total.
- Jours comptés du jour de départ inclus au jour d’arrêt exclu ; une option permet de compter aussi le dernier jour.
- Arrondi des intérêts au centime par période ; total arrondi aux 5 centimes par défaut (option désactivable).
- Intérêt simple, sans capitalisation (art. 105 al. 3 CO).

## Réquisition de poursuite

Le texte généré suit les rubriques du formulaire de réquisition : montant de la créance, taux et date dès laquelle les intérêts courent, titre ou cause de l’obligation. L’office des poursuites ne calcule pas les intérêts. La réquisition doit être déposée dans une langue officielle de l’office.
