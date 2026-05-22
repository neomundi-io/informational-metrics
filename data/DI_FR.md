# Di - Densité informationnelle

## Version française de travail

Ce document présente une définition publique et méthodologique de la densité informationnelle utilisée dans le cadre NeoMundi.

Il ne divulgue pas les coefficients de production, les paramètres propriétaires, les seuils, les pondérations internes, les règles décisionnelles complètes, ni les mécanismes d’inférence runtime utilisés dans le moteur NeoMundi.

## Définition

La densité informationnelle désigne une lecture relative de la concentration, de la transformation ou de la dissipation informationnelle observée pendant une génération IA ou un segment d’exécution.

Elle vise à qualifier la relation entre l’information produite, le volume généré, l’effort informationnel mobilisé et le niveau de risque ou d’incertitude associé.

Dans le cadre NeoMundi, Di ne doit pas être comprise comme une mesure absolue de vérité ou de qualité.

Elle constitue un indicateur méthodologique permettant d’observer comment une génération transforme et stabilise l’information dans un contexte donné.

## Rôle de la densité informationnelle

La densité informationnelle permet d’aller au-delà de la simple volumétrie.

Deux réponses peuvent avoir un volume similaire, mais présenter une densité informationnelle différente.

Di aide à distinguer :

- une réponse longue mais pauvre en information utile ;
- une réponse courte mais fortement concentrée ;
- une réponse dense et stable ;
- une réponse dense mais risquée ;
- une réponse verbeuse avec faible valeur informationnelle ;
- une réponse qui mobilise beaucoup d’effort informationnel pour un résultat peu exploitable.

## Interprétation

Une densité informationnelle élevée peut indiquer une réponse riche, concentrée ou fortement structurée.

Mais une densité élevée n’est pas automatiquement positive.

Une réponse peut être dense et pourtant instable, trompeuse ou insuffisamment vérifiée.

Une densité informationnelle faible peut indiquer une réponse diffuse, répétitive ou pauvre en information exploitable.

Mais une densité faible n’est pas automatiquement négative.

Certaines tâches pédagogiques, narratives ou explicatives peuvent nécessiter plus d’espace, plus de contexte et donc une densité apparente plus faible.

## Ce que Di ne prétend pas mesurer

Di ne prétend pas mesurer :

- la vérité sémantique absolue ;
- la certitude factuelle ;
- la qualité humaine complète d’une réponse ;
- la stabilité de gouvernance à elle seule ;
- la présence ou l’absence certaine d’hallucination ;
- la compréhension interne du modèle ;
- la responsabilité juridique d’une génération ;
- une énergie physique réelle.

Di mesure une relation informationnelle conventionnelle, pas une vérité universelle.

## Relation avec la volumétrie

La volumétrie observe les volumes manipulés.

Di introduit une lecture plus interprétative de la manière dont ces volumes sont transformés en information exploitable, dense, diffuse ou dissipée.

La volumétrie répond à la question :

Combien d’information a été manipulée ?

Di contribue à répondre à la question :

Quelle forme informationnelle cette production semble-t-elle prendre ?

## Relation avec Dv

Dv observe le rapport entre volume de sortie et volume d’entrée.

Di observe une densité informationnelle relative.

Une réponse peut avoir une forte expansion volumétrique mais une densité informationnelle faible si elle répète, dilue ou sur-explique.

Une réponse peut avoir une faible expansion volumétrique mais une densité informationnelle élevée si elle concentre fortement l’information.

## Relation avec E

E observe une charge ou un effort informationnel.

Di observe une densité ou une relation informationnelle associée à cette charge.

E et Di doivent être interprétées ensemble.

Une énergie informationnelle élevée peut être pertinente si elle correspond à une densité informationnelle utile.

Elle peut être problématique si elle correspond à une forte dépense informationnelle pour une faible valeur exploitable.

## Relation avec G et ΔG

Di ne remplace pas G.

G observe un état de stabilité de gouvernance.

ΔG observe une variation de stabilité au cours du temps.

Di observe une densité informationnelle relative.

Ces signaux peuvent être corrélés, mais ils ne mesurent pas la même chose.

Une génération peut être dense mais instable.

Une génération peut être stable mais peu dense.

Une génération peut être longue, dense et stable.

Une génération peut être longue, diffuse et instable.

C’est précisément l’intérêt d’une lecture multi-signaux.

## Usage dans un cadre de gouvernance

Dans un système de gouvernance runtime, Di peut contribuer à :

- contextualiser la qualité informationnelle d’une génération ;
- identifier des réponses verbeuses ou diluées ;
- repérer des réponses très concentrées nécessitant une vérification ;
- compléter les signaux de stabilité ;
- enrichir les analyses d’audit ;
- fournir une couche supplémentaire d’observabilité.

Di ne doit pas déclencher seule une décision de gouvernance.

Elle doit être interprétée avec les autres signaux, le contexte métier, les seuils appliqués et le niveau de risque attendu.

## Position méthodologique

La densité informationnelle est une métrique d’observabilité informationnelle.

Elle vise à rendre visible une dimension souvent ignorée des systèmes génératifs : la manière dont une réponse transforme un volume en information plus ou moins dense, exploitable ou dissipée.

Elle ne prétend pas fournir une note absolue de qualité.

Elle sert à enrichir l’interprétation, pas à remplacer le jugement humain ou les autres signaux de gouvernance.

## Limites

La densité informationnelle dépend fortement du contexte.

Une bonne réponse juridique, médicale, scientifique ou pédagogique peut nécessiter une densité différente selon le cas d’usage.

Une réponse très dense peut être difficile à interpréter.

Une réponse peu dense peut être volontairement pédagogique.

Di doit donc toujours être lue dans son contexte d’usage.

Les paramètres de production, coefficients internes et règles d’intégration au moteur NeoMundi relèvent de l’implémentation propriétaire et ne sont pas documentés dans ce dépôt public.
