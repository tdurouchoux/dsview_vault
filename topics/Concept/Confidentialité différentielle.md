---
type: Concept
---

La confidentialité différentielle est une technique de protection de la vie privée qui garantit que les données individuelles ne peuvent pas être déduites à partir des résultats d'une analyse de données agrégées. Elle est souvent utilisée pour publier des statistiques tout en protégeant la vie privée des individus. Cette méthode ajoute du bruit aux données pour empêcher l'identification des individus tout en préservant l'utilité globale des données. In federated learning, it helps to ensure that the presence or absence of any single user's data does not significantly affect the global model, thereby protecting user privacy. This technique involves carefully bounding the impact of any possible user contribution and adding random noise to the training process.