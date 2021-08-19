# IHM-Maroc-Telecom
Interface graphique de paiement en ligne IAM pour le paiement de facture en ligne réalisée en **Java**.

# Description
il y a trois types de factures :
+ Mobile
+ Fixe
+ Internet

On va s’intéresser uniquement au paiement de la facture du téléphone mobile.
Lorsque le client choisit un type de facture une fenêtre s’ouvre et lui demande de s’authentifier.
Comme informations sur le client, on lui demande :
1. Son numéro de téléphone
2. Son code Fidelio
3. Son email pour lui envoyer la facture
4. Son accord d’avoir lu et accepté les conditions particulières d'utilisation, notamment la mention relative à la protection des données personnelles.

Une fois le client fournit les informations demandées, on peut :
+ Soit le faire sortir de l’application s’il souhaite annuler
+ Soit on le dirige vers une autre fenêtre pour consulter et payer ses factures

Les informations demandées au client pour le paiement sont :
1. Méthode de paiement : « VISA, MASTERCARD, CMI, MAESTRO »
2. Numéro de la carte de paiement
3. Date d'expiration ou on précise le Mois et l’Année
4. Code de vérification de la carte
5. Son accord d’avoir lu et accepté les conditions générales d’utilisation du service

Une fois le client fournit les informations demandées, on doit :
+ Soit le faire sortir de l’application s’il souhaite annuler
+ Soit valider son paiement et lui envoyer sa facture (Un message confirme l’envoi du reçu
de paiement)

# Techonologies utilisées
+ Java
+ MySQL Database
