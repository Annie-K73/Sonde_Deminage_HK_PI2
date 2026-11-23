# Proposition IHM – Restitution des informations

## Objectif

Informer l'opérateur de l'état du système et des éventuelles détections suspectes, sans le surcharger d'informations ni multiplier les alertes inutiles. 
Le robot équipé de la sonde effectuant des mesures à intervalles réguliers, la restitution doit privilégier les événements importants plutôt qu'une notification systématique.

## 1. Signalisation sonore locale

Le son constitue le principal moyen d'alerte envisagé, conformément aux retours du client (Hear & Know) :

| Situation | Signal envisagé |
|---|---|
| Mesure effectuée, sans indice suspect | Aucun signal sonore |
| Détection d'un objet suspect | Signal sonore distinct et facilement identifiable |
| Mesure inexploitable ou défaut du système | Signal sonore spécifique |

**Principe :** éviter un signal sonore à chaque mesure normale afin de limiter l'accoutumance aux alertes et de préserver la vigilance de l'opérateur.

## 2. Signalisation lumineuse (LED)

Des LED pourraient compléter la signalisation sonore pour fournir une indication visuelle locale. L'intérêt et les modalités de cette signalisation restent à valider.

- État normal : led VERTE
- Détection suspecte : led ROUGE
- Défaut du système : led ORANGE


## 3. Écran déporté

Conformément aux échanges avec le client, l'écran serait réservé aux informations nécessitant une consultation plus détaillée.

| Catégorie | Informations à afficher |
|---|---|
| État général | État du système, communication avec le robot |
| Mesures | Profondeur, inclinaison de la sonde, dernières mesures |
| Détection | Résultat de l'analyse, présence éventuelle d'un objet suspect |
| Historique | Liste des détections et résultats précédents |

En cas de détection suspecte, l'écran devra notamment permettre à l'opérateur de retrouver la mesure concernée et de consulter les informations associées.

## 4. Principes ergonomiques retenus

- Limiter les notifications aux événements nécessitant réellement l'attention de l'opérateur.
- Éviter la répétition des alertes pour une même détection persistante.
- Distinguer clairement une détection suspecte d'un défaut de fonctionnement.
- Hiérarchiser les informations : état général et alertes en priorité, données techniques en consultation secondaire.

