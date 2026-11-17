# Hackathon DuploJS — Étude de transpilation vers Go

17–20 novembre 2026 · ESGI · Équipes de trois à quatre

## La question

Peut-on transpiler du DuploJS vers Go pour obtenir un programme performant tout en conservant le comportement d'origine ?

L'idée est de profiter de l'expressivité et de la robustesse de DuploJS pendant le développement, puis de générer du Go pour son exécution en production. La faisabilité de cette approche est précisément ce que vous allez étudier.

## Les projets

Le boilerplate est disponible sur GitHub : <https://github.com/duplojs/hackathon-11-2026>.

Toutes les équipes étudient les **dix exercices, de 01 à 10**, dans le dossier `projects/` du boilerplate. Chaque projet présente des exemples d'utilisation de DuploJS et les problématiques à résoudre.

Le **projet 00** sert d'exemple : sa solution et les transformers correspondants fournissent un point de départ. Il ne compte pas parmi les dix exercices à réaliser. Il ne s'agit pas de prendre en charge tout TypeScript.

## Votre démarche

1. **Analysez** les comportements et les éléments à transformer. Étudiez leurs variations possibles, au-delà des seuls exemples fournis.
2. **Imaginez et justifiez** des stratégies de transformation génériques et composables. Recherchez un Go qui conserve le comportement attendu et dont les représentations sont adaptées à l'exécution et à la gestion de la mémoire.
3. **Implémentez** vos stratégies sous forme de transformers dans le boilerplate. Examinez le Go produit ; vous pouvez aussi écrire ou exécuter du Go pour explorer vos solutions.
4. **Documentez** votre raisonnement, vos choix, vos observations et leurs limites. Pour chaque exercice abordé, précisez les problèmes étudiés, les solutions proposées, les résultats observés et les limites. Si vous ne trouvez pas de solution ou si elle vous paraît impossible, expliquez pourquoi.

L'objectif n'est pas de reproduire à l'identique les types TypeScript. Justifiez le recours à des représentations génériques comme `any` lorsqu'il vous semble nécessaire : elles peuvent préserver le comportement sans apporter les bénéfices de performance recherchés.

La performance ne se réduit pas à la vitesse : prenez aussi en compte les ressources utilisées, notamment la mémoire. Aucune mesure de performance ni infrastructure de tests comparatifs n'est imposée ; distinguez vos observations de ce qui reste à vérifier.

## Collaboration et outils

L'entraide et le partage de réflexions entre équipes sont encouragés. Chaque équipe présente et justifie sa propre démarche.

Les outils de développement, assistants et agents IA sont autorisés. Si vous utilisez un agent IA, vous pouvez vous en servir pour rédiger un **skill** qui rassemble les règles issues de votre réflexion, encadre les exemples et guide l'implémentation. Utilisez ensuite ce cadre pour développer vos solutions et leur documentation de manière structurée.

Chaque équipe définit ses règles et reste responsable de ses choix et du résultat présenté.

## Travail à transmettre

1. Faites un **fork** du dépôt du boilerplate et partagez-le avec votre équipe.
2. Dans le README du boilerplate, renseignez les noms, prénoms et classes de tous les membres. Documentez les projets étudiés, les stratégies et leur justification, les variations et limites, les résultats observés et les étapes pour les reproduire.
3. Ouvrez une **pull request** vers le dépôt du boilerplate.
4. Remettez aux organisateurs une **archive ZIP** du projet au moment de la soutenance, correspondant au travail présenté dans la pull request.

## Évaluation et restitution

La note et le commentaire sont collectifs puis reportés individuellement. L'avancement sur les exercices, la qualité du raisonnement et des solutions, leur mise en œuvre, la documentation et la restitution sont valorisés. Une limite argumentée peut contribuer à l'étude.

Vous disposez de **10 minutes** pour présenter votre démarche, vos résultats, vos choix et leurs limites. Aucun diaporama n'est imposé.
