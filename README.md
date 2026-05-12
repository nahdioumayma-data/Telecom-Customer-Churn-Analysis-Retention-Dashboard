# Telecom Churn Insights Dashboard


## 📋 Aperçu du Projet
Ce dépôt contient un tableau de bord analytique conçu pour comprendre pourquoi les clients quittent le service de télécom. Avec un **Taux de Churn de 26,86 %**, l'analyse se concentre sur les leviers permettant de réduire ce chiffre.

### Points Clés (KPIs) :
* **Total Clients :** 6 687
* **Clients Perdus :** 1 796
* **Taux de Churn :** 26,86 %

## 📊 Structure du Tableau de Bord

### 1. Vue d'Ensemble (Overview)
*Analyse des motifs de départ et distribution par type de contrat.*
*    montre que la concurrence ("Competitor") est le premier facteur de churn.
*   Les contrats "Month-to-Month" (Mois par mois) représentent plus de la moitié de la base client (51,01 %) mais sont les plus volatils.

### 2. Segmentation et Démographie
*Étude de la corrélation entre l'âge, les frais mensuels et la perte de clients.*
* révèle une augmentation drastique du churn chez les clients de plus de 65 ans.
*   Le churn rate est inversement proportionnel à l'ancienneté du compte (Account Length).

### 3. Analyse de l'Usage et des Frais
*Impact des services techniques et de la consommation de données.*
*    souligne que les clients ayant un plan de données illimité ont, paradoxalement, un taux de churn élevé lorsqu'ils consomment moins de 5 Go.
*   Mise en évidence du lien entre le nombre d'appels au service client et la probabilité de départ.

## 🛠️ Outils Utilisés
*   **Visualisation :** Power BI / Tableau (selon votre outil)
*   **Source de données :** Dataset Telecom (DATACAMP)
*   **Nettoyage de données :** Power Query / Python (Pandas)

## 💡 Recommandations Stratégiques
*   **Ciblage Senior :** Améliorer l'assistance technique pour les tranches d'âge 65+.
*   **Conversion de Contrat :** Inciter au passage des contrats mensuels vers des contrats annuels via des remises.
*   **Service Client :** Intervenir proactivement dès que le nombre d'appels au support dépasse une certaine limite.

---
*Projet réalisé dans le cadre d'une analyse de Data Visualisation.*
