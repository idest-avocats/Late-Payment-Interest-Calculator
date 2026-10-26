# Cas de test

Cas calculés à la main et vérifiés avec l’outil (version 1.0). À refaire après chaque modification. Méthode par défaut, sauf mention : jours calendaires / 365, jour d’arrêt exclu, total arrondi aux 5 centimes.

| # | Données | Résultat attendu | Point contrôlé |
|---|---|---|---|
| 1 | CHF 10'000 à 5 % dès le 01.01.2026, arrêté au 01.01.2027 | intérêts CHF 500.00 | année entière, 365 jours |
| 2 | Même créance, arrêtée au 31.12.2026, dernier jour compté | intérêts CHF 500.00 | option « compter le dernier jour » |
| 3 | Cas 1 avec un acompte de CHF 1'000 le 01.07.2026 | capital CHF 9'247.95 ; intérêts CHF 233.10 ; intérêts dès le 01.07.2026 | imputation sur les intérêts (247.95) puis sur le capital (art. 85 CO) |
| 4 | Cas 1 avec un acompte de CHF 100 le 01.07.2026 | intérêts échus impayés CHF 147.95 (01.01 au 30.06.2026) ; total des intérêts CHF 400.00 | intérêts échus en créance distincte, sans intérêts (art. 105 al. 3 CO) |
| 5 | CHF 10'000 à 5 %, variante 30/360, du 01.01.2026 au 01.01.2027 | intérêts CHF 500.00 | 360 jours |
| 6 | Variante 30/360, du 31.01.2026 au 01.03.2026 | 31 jours | les 31 comptent comme 30 |
| 7 | CHF 12'500 à 5 % du 15.03.2026, arrêté au 15.10.2026 | 214 jours ; intérêts CHF 366.44 ; total CHF 12'866.45 | calcul simple, arrondi aux 5 centimes |
| 8 | CHF 12'500 à 5 % dès le 15.03.2026, acompte de CHF 100 le 30.06.2026, frais de CHF 50 à 0 %, arrêté au 15.10.2026 | total CHF 12'816.45 (capital 12'550.00, intérêts 266.44, arrondi aux 5 centimes) ; réquisition : CHF 12'500 avec intérêt dès le 30.06.2026, CHF 83.22 d’intérêts échus sans intérêts, CHF 50 sans intérêt | scénario complet et textes générés |
| 9 | Taux saisi de 3 % | alerte : taux légal de 5 % (art. 104 al. 1 CO) | contrôle du taux |
| 10 | Langue EN (`?lang=en`) | mêmes montants ; textes en anglais avec mention de la langue officielle | version anglaise |
| 11 | CHF 100'000 à 5 % du 01.01.2026, arrêté au 26.10.2026 | 298 jours ; intérêts CHF 4'082.19 ; total CHF 104'082.20 | méthode par défaut, exemple de la rubrique « Bases de calcul » |
| 12 | Même cas, variante 30/360 européenne | 295 jours ; intérêts CHF 4'097.22 ; total CHF 104'097.20 | mois de 31 jours et février comptés pour 30 jours |
| 13 | Même cas, variante jours calendaires / 360 | 298 jours ; intérêts CHF 4'138.89 ; total CHF 104'138.90 | même nombre de jours que la méthode par défaut, diviseur 360 |
| 14 | CHF 50'000 à 5 % du 01.01.2025, arrêté au 26.10.2026, variante 30/360 européenne | 655 jours ; intérêts CHF 4'548.61 ; total CHF 54'548.60 | identique à l'aide au calcul des intérêts de l'Office des poursuites de Genève |

© 2026 id est avocats Sàrl, sous licence [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.fr).
