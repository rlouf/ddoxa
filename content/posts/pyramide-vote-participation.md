+++
title = "La pyramide du vote I - Participation"
author = ["Rémi Louf"]
description = "Age médian en supposant que tous les 18-35 ans votent"
date = 2022-03-10
tags = ["visualisation"]
draft = false
math = true
+++

Une période électorale qui se respecte se doit de rappeler quelques lieux communs. Avec la montée des taux d'abstention et du commentariat professionnel s'est installée l'idée que si les jeunes ont à subir des politiques menées pour séduire les plus âgés, c'est bien parce qu'ils ne votent pas.

On ne peut pas nier que le _taux_ d'abstention des jeunes est élevé. Regardons par exemple les intentions de participations pour la présidentielle 2022 telles que données par le [sondage Ipsos du 3 mars 2022 pour la fondation Jean-Jaurès et Le Monde](https://www.ipsos.com/sites/default/files/ct/news/documents/2022-03/Ipsos%20-%20Enque%CC%82te%20Electorale%20-%20Vague%206%20-%205%20mars%202022.pdf) :

| Âge            | Participation (preque) certaine |
|----------------|---------------------------------|
| 18-24          | 61%                             |
| 25-34          | 67%                             |
| 35-50          | 76%                             |
| 50-60          | 79%                             |
| 60-70          | 85%                             |
| 70 ans et plus | 91%                             |

La différence est nette, avec 30 points de pourcentage de différence entre les plus jeunes (18-24 ans) et les plus âgés (70 ans et plus).

Mais ce n'est pas si simple. Le résultat du vote est déterminé par un pourcentage du _corps électoral_, mais les pourcentages donnés plus haut ne disent rien de la répartition par classe d'âge du corps électoral. Or **avant même de parler d'abstention, la pyramide des âges introduit une déformation importante dans la distribution des votes**.

Pour le voir on représente la population par année révolue [donnée par l'INSEE](https://www.insee.fr/fr/statistiques/2381472) (gris), et on représente la population qui est certaine ou presque certaine d'aller voter sur le même graphique (en noir) en utilisant les données du tableau précédent :

{{< figure src="/ox-hugo/pyramide-vote-abstention-pyramide.png" caption="<span class=\"figure-number\">Figure 1: </span>Pour obtenir la pyramide des âges des personnes certaines d'aller voter on applique le pourcentage de participation de façon uniforme à toute la tranche d'âge correspondante. Ce qui donne un rendu un peu surprenant pour les centenaires par exemple, mais sans vraiment affecter les conclusions." >}}

La représentation graphique est parlante, mais pour ne pas en tirer les mauvaises conclusions calculons la quantité qui nous intéresse: l'âge qui sépare le corps électoral en deux i.e. pour lequel les personnes plus âgées ont la majorité absolue. C'est-à-dire, l'âge médian d'abord du corps électoral, puis des personnes (presque) certaines d'aller voter. S'ils sont proches c'est la pyramide des âges qui est en cause plutôt que les différences en termes de participation.

L'âge médian du corps électoral est de _50 ans_, alors que celui des personnes (presque) certaines d'aller voter de _53 ans_[^1]. **On passe donc beaucoup de temps à déplorer le taux d'abstention des jeunes, mais c'est surtout la pyramide des âges qui est déterminante.**

[^1]: Le chiffre de 53 ans pour l'âge médian des personnes (presque) certaines d'aller voter est à prendre avec des pincettes. En effet, les taux de participation sont données par tranche d'âge, et la distribution à l'intérieur de ces tranches est susceptible d'avoir une (faible) influence sur l'âge médian. Il serait envisageable de calculer la distribution des âges médians plausibles, mais cela prendrait du temps et je ne m'attends pas à ce que cela change les conclusions.

> Les plus de 50 ans sont en majorité absolue dans le corps électoral.

Cette analyse simple soulève plusieurs questions auxquelles j'essaierai de répondre dans les prochaines notes:

1.  Est-ce que ceci a toujours été le cas : quelle a été l'évolution de l'âge médian du corps électoral dans les 50 dernières années ?
2.  Est-ce que cela a de l'importance : est-ce qu'il y a un vote différencié en fonction de l'âge ? Si oui, qui est le candidat des jeunes ?

_Cet article soulève d'autes questions pour vous ? J'ai fait une erreur ? N'hésitez pas à me contactez ([@remilouf](https://twitter.com/remilouf)) sur Twitter !_
