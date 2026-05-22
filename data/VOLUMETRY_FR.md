# Volumétrie - Métrique de volume informationnel

## Version française de travail

Ce document présente une définition publique et méthodologique de la volumétrie utilisée dans le cadre NeoMundi.

Il ne divulgue pas les paramètres propriétaires, les seuils de production, les règles décisionnelles complètes, ni les mécanismes internes utilisés dans le moteur NeoMundi.

## Définition

La volumétrie désigne l’observation du volume informationnel manipulé ou produit pendant une génération IA ou un segment d’exécution.

Elle décrit des grandeurs simples, mesurables et auditables, telles que :

- le volume d’entrée ;
- le volume de sortie ;
- la longueur de la génération ;
- le nombre de tokens traités ;
- le nombre de fenêtres d’exécution observées ;
- le rapport entre le volume demandé et le volume produit.

La volumétrie ne mesure pas la qualité d’une réponse.  
Elle fournit un contexte de mesure pour interpréter les autres métriques informationnelles.

## Rôle de la volumétrie

La volumétrie sert de socle descriptif.

Elle permet de situer une génération dans son contexte de production :

- réponse courte ou longue ;
- compression ou expansion de l’information ;
- faible ou forte charge de génération ;
- comparaison entre plusieurs sorties ;
- analyse des effets liés à la longueur ;
- contrôle des biais liés au volume.

Dans un système de gouvernance runtime, la volumétrie aide à éviter une interprétation isolée des signaux.

Une réponse longue ne doit pas être considérée comme instable uniquement parce qu’elle est longue.  
Une réponse courte ne doit pas être considérée comme fiable uniquement parce qu’elle est concise.

## Variables observables

Les variables volumétriques peuvent inclure notamment :

- `tokens_in` : volume de tokens en entrée ;
- `tokens_out` : volume de tokens en sortie ;
- `total_tokens` : volume total traité ;
- `input_output_ratio` : rapport entre entrée et sortie ;
- `execution_windows` : nombre de fenêtres runtime observées ;
- `segment_length` : longueur d’un segment analysé.

Ces variables sont descriptives.  
Elles ne constituent pas, à elles seules, une décision de gouvernance.

## Interprétation

La volumétrie peut aider à distinguer plusieurs situations :

- une réponse brève à faible charge informationnelle ;
- une réponse longue mais stable ;
- une réponse longue et instable ;
- une réponse courte mais risquée ;
- une forte expansion informationnelle ;
- une contraction ou synthèse de l’information.

Elle permet également de mieux comprendre certaines métriques dérivées, comme la densité volumétrique, l’énergie informationnelle ou la densité informationnelle.

## Ce que la volumétrie ne prétend pas mesurer

La volumétrie ne prétend pas mesurer :

- la vérité sémantique ;
- la certitude factuelle ;
- la cohérence interne ;
- la qualité humaine d’une réponse ;
- la stabilité de gouvernance ;
- la présence ou l’absence d’hallucination ;
- la responsabilité juridique d’une génération.

Elle mesure un volume, pas une validité.

## Relation avec les autres métriques

Dans le cadre NeoMundi, la volumétrie sert de base à d’autres métriques informationnelles.

Elle peut contribuer à contextualiser :

- la densité volumétrique ;
- l’énergie informationnelle ;
- la densité informationnelle ;
- les signaux de stabilité ;
- les décisions de gouvernance.

La volumétrie ne remplace pas les signaux comme G ou ΔG.  
Elle fournit une couche de contexte permettant de mieux interpréter les variations observées.

## Position méthodologique

La volumétrie est une métrique descriptive et non décisionnelle.

Elle est utile parce qu’elle rend visible la quantité d’information manipulée par un système IA pendant son exécution.

Elle doit toujours être interprétée avec d’autres signaux, notamment les signaux de stabilité, de risque, de densité et de gouvernance.

## Limites

La volumétrie peut être facilement mesurée, mais elle peut être mal interprétée.

Un volume élevé peut correspondre à une réponse utile, structurée et stable.  
Un volume faible peut correspondre à une réponse insuffisante, ambiguë ou trompeuse.

La volumétrie ne doit donc jamais être utilisée seule pour conclure à la qualité, à la stabilité ou à la fiabilité d’une génération IA.
