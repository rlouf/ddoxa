+++
title = "Note #2 - La pyramide du vote: depuis 1958"
author = ["Rémi Louf"]
description = "Pyramide des âges dans la 5e République"
date = 2022-03-13
tags = ["visualisation"]
draft = false
+++

Dans la [première note de cette série]({{< relref "pyramide-vote-participation" >}}) nous nous sommes intéressé à la pyramide des âges du corps électoral français et la façon dont elle est déformée par l'abstention. L'âge médian du corps électoral est de 50 ans en 2022. Ce chiffre paraît élevé au premier abord, mais avant d'affirmer que la démographie est responsable d'une mutation politique encore faudrait-il que l'âge médian ait été plus faible par le passé.

Un [article édité par l'INED](https://www.ined.fr/fichier/s_rubrique/18851/pop_et_soc_francais_110.fr.pdf) en 1978 nous donne la réponse pour la première moitié du XXe siècle. L'âge médian du corps électoral a augmenté en même temps que la part des plus de 65 a augmenté dans la population :

{{< figure src="/ox-hugo/FN4eQi-X0AASDUu.png" >}}

Qu'en est-il de la période plus récente ? Regardons, puisque c'est cela qui nous intéresse, l'évolution de l'âge médian depuis les premières élections au suffrage universel de la Ve République, en 1965. Nous utilisons les [données démographiques historiques données par l'INSEE](https://www.insee.fr/fr/statistiques/3312958) :

{{< figure src="/ox-hugo/pyramide-age-median.png" >}}

Il est utile de rappeler pour comprendre le passage de 1974 à 1981 que [la majorité est passée de 21 ans à 18 ans en 1974](https://www.leparisien.fr/archives/la-majorite-a-18-ans-c-etait-il-y-a-quarante-ans-05-07-2014-3978415.php).  L'äge médian atteint donc son minimum en 1988 pour l'élection de François Mitterrand et n'a jamais cessé de croïtre depuis, Pour mieux comprendre la tendance il peut être utile de visualiser l'évolution de la pyramide des âges en parallèle :

{{< figure src="/ox-hugo/pyramide-median-animation-optimized.gif" >}}

La conclusion est claire :

> L'âge médian de l'électorat n'a jamais été aussi élevé et continue encore d'augmenter.

Ceci est d'autant plus vrai que, comme nous l'avons vu dans la [note #1]({{< relref "pyramide-vote-participation" >}}), la participation augmente avec l'âge. Pour aller plus loin, quelques idées et suggestions:

1.  On pourrait pondérer les pyramides des âges par la participation donnée par les sondages à la sortie des urnes (lorsque ces sondages sont disponibles). En particulier je me demande s'il existe une corrélation entre la participation des plus jeunes et l'âge moyen du corps électoral; l'idée étant que l'incitation à participation pourrait être faible lorsque le résultat est perçu comme connu à l'avance.
2.  Il devrait être possible de projeter la démographie du corps électoral sur les 18 prochaines années avec un modèle relativement simple qui apprend la probabilité de passer d'une année à l'autre. On peut s'attendre à ce que l'âge médian continue d'augmenter, mais pour combien de temps encore ?

Beaucoup de réactions indignées à la note #1. Presque toutes partent du principe que l'âge est un facteur explicatif du vote, c'est-à-dire qu'une classe d'âge vote pour protéger les intérêts qui lui sont propores. Les plus âgés votent à droite, les plus jeunes à gauche c'est bien connu. En sommes-nous si sûrs ? Dans la prochaine note nous nous intéresserons à la pyramide des âges des intentions de vote pour les différents candidats à la prochaine présidentielle. Et nous verrons qui est réellement le candidat des jeunes.
