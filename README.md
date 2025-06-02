# Projet Power BI : Développement d'un tableau de bord d'analyse des ressources humaines

Dans le cadre de ce projet, nous avons conçu un tableau de bord interactif dédié à l’analyse des ressources humaines. L’objectif principal est de fournir une vision claire, structurée et dynamique des données RH, afin d’aider à la prise de décision stratégique en entreprise.

Ce tableau de bord permet de visualiser et d’explorer différentes dimensions clés telles que la satisfaction au travail, la performance de la structure, la répartition des rôles professionnels, le genre, la situation maritale, et bien d’autres indicateurs pertinents.

Les principales étapes de ce projet sont :

- L’importation des données
- Le nettoyage et la transformation des données
- La création d'un tableau de bord

## 🔧 Importation, nettoyage et transformation des données

Après avoir importé les données dans Power BI et accédé à l’éditeur Power Query, la première étape consiste à activer certaines options d’affichage pour obtenir une vue d’ensemble sur la qualité des données :

- Distribution des colonnes
- Profil de colonne
- Qualité de colonne
  
<img width="957" alt="1" src="https://github.com/user-attachments/assets/7a4d6f26-8002-4a78-99cb-06ac9a51672c" />

Ensuite, nous définissons la première ligne comme en-têtes de colonnes. Pour cela, dans l’onglet Accueil, on clique sur "Utiliser la première ligne pour les en-têtes".

<img width="953" alt="2_entetes" src="https://github.com/user-attachments/assets/9c681a3e-cd4c-4dce-928a-c075247921f8" />

Nous procédons ensuite à la suppression des colonnes inutiles, ici les colonnes -2 et 0.

<img width="959" alt="suppre_colonne1" src="https://github.com/user-attachments/assets/66ee16df-4fd6-4847-b382-e6e6ff7fe408" />

<img width="958" alt="suppre_colonne2" src="https://github.com/user-attachments/assets/6f116e04-465a-4073-b9f9-0466ef851e28" />

Puis, nous modifions le type de données de la colonne "Job Level" en Texte. Pour cela, on sélectionnez la colonne, on va dans Transformer, on clique sur "Type de données", puis on choisit Texte.

Le nettoyage et la transformation des données sont maintenant terminés. Passons à la création du tableau de bord.

## 📊 Visualisation : Tableau de bord RH

La création du tableau de bord étant relativement longue, elle ne sera pas détaillée ici. Pour une explication approfondie du processus de création, veuillez consulter le projet "Power BI Avancé" disponible dans un de mes dépots GitHub.

Voici un aperçu du tableau de bord final :

<img width="958" alt="tableau_de_bord1" src="https://github.com/user-attachments/assets/ea5b53c4-4762-4f45-8c35-d99163c4c927" />

<img width="511" alt="tableau_de_bord2" src="https://github.com/user-attachments/assets/f817ba8a-044b-4302-879e-4aacf5f38f3a" />


#### Et les visualisations filtrées selon le statut marital :

<img width="509" alt="tableau_de_bord2_M" src="https://github.com/user-attachments/assets/60f12eee-ec30-461a-b36c-62bb248348c0" />

<img width="511" alt="tableau_de_bord2_D" src="https://github.com/user-attachments/assets/ab9aa2d0-dc12-4ff2-914c-59baf1b19e05" />

<img width="511" alt="tableau_de_bord2_S" src="https://github.com/user-attachments/assets/1ece10c1-c145-4a5c-83c9-bf224b024f44" />

Ce projet constitue une démonstration concrète de l’utilisation de Power BI pour valoriser des données RH, automatiser les rapports et appuyer des décisions basées sur les données.
