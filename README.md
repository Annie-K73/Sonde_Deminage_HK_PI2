# Implémentation IHM – Sonde de déminage 2.0

**Autrice :** Annie KADIAMBU (CCC A4)  
**Dernière mise à jour :** 17/11/2026

## 1. Démarche de développement

Pour le développement de l'IHM, je souhaite adopter une démarche agile, avec un fonctionnement par petites itérations successives. L'objectif est de pouvoir avancer sur l'interface indépendamment des groupes travaillant sur la robotique, l'électronique et le Machine Learning, sans attendre que leurs développements soient terminés.

Le principe est de commencer par une première version simple et fonctionnelle, puis de l'enrichir progressivement en fonction de l'avancement du projet et des besoins identifiés.

## 2. Vue d'ensemble

Le développement suivra plusieurs étapes :

1. **Définition des besoins :** identifier les besoins de l'opérateur et les informations pertinentes à afficher.
2. **Structuration des données :** identifier les données susceptibles d'être transmises par les capteurs et définir leur organisation.
3. **Première maquette :** concevoir une première interface et définir son organisation générale.
4. **Premier affichage :** créer une interface fonctionnelle alimentée par des données fictives.
5. **Visualisation des mesures :** intégrer progressivement des indicateurs et des graphiques.
6. **Intégration :** connecter l'interface aux données réelles transmises par les autres sous-systèmes.
7. **Validation :** tester l'ergonomie, la lisibilité et le fonctionnement général de l'interface.

Cette approche permettra d'avoir rapidement un support concret à présenter à l'équipe, de tester les choix ergonomiques en amont et d'adapter l'interface au fur et à mesure.

## 3. Backlog IHM

### Fondations
- [ ] Identifier les besoins de l'opérateur.
- [ ] Définir les données nécessaires à l'IHM.
- [ ] Créer une base de données fictive pour les premiers essais.
- [ ] Réaliser une première maquette de l'interface.

### Affichage
- [ ] Afficher les mesures principales (force, inclinaison, profondeur, signal piézoélectrique...).
- [ ] Créer des graphiques pour visualiser l'évolution des mesures.
- [ ] Organiser les informations selon leur importance pour l'opérateur.

### Intégration
- [ ] Définir le format d'échange des données avec les groupes électronique et robotique.
- [ ] Définir les informations attendues du groupe Machine Learning.
- [ ] Connecter l'IHM au prototype.
- [ ] Gérer les états du système et les éventuelles erreurs de communication.

### Validation
- [ ] Effectuer des tests ergonomiques.
- [ ] Recueillir les retours de l'équipe.
- [ ] Améliorer l'interface en fonction des résultats des tests.
- [ ] Finaliser et documenter l'IHM.

## 4. Livrables attendus

| Étape | Livrable |
|---|---|
| Fondations | Cahier des besoins IHM et première maquette |
| Affichage | Première version fonctionnelle avec données fictives |
| Visualisation | Tableau de bord avec graphiques et indicateurs |
| Intégration | Interface connectée au prototype |
| Validation | Version stabilisée et documentée |

## 5. Coordination avec les autres groupes

Le développement de l'IHM nécessite des échanges réguliers avec les autres groupes.

| Groupe | Informations attendues |
|---|---|
| Électronique | Mesures disponibles, unités, fréquence d'échantillonnage et format des données |
| Robotique | Position, profondeur, inclinaison et état du robot |
| Machine Learning | Classes de classification, résultats d'analyse et éventuels scores de confiance |

Ces informations seront précisées progressivement afin de permettre une intégration cohérente des différents sous-systèmes.

---

*Ce document sera mis à jour au fur et à mesure de l'avancement du développement.*
