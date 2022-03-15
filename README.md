# microservices-e-commerce

Cette application est composée de 3 microservices :

#### 1)- Microservice-produits :
ce microservice gère le produit. Il propose 2 opérations simples : lister tous les produits, et récupérer un produit par son ID.

#### 2)- Microservice-commandes :
microservice de gestion des commandes. Il permet de passer une commande et de récupérer une commande par son ID.

#### 3)- Microservice-paiements :
ce microservice permet de simuler le paiement d'une commande. Une fois le paiement enregistré, il fait appel au Microservice-commandes pour mettre à jour le statut de la commande.
