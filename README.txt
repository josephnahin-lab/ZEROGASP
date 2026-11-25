ZEROGASPIL CI — PROTOTYPE WEB
============================

OUVRIR LE PROTOTYPE
1. Décompressez le fichier ZIP.
2. Ouvrez le dossier zerogaspil-ci.
3. Double-cliquez sur index.html pour lancer le prototype dans un navigateur récent.

PARCOURS D’ENTRÉE
1. À l’ouverture, cliquez sur l’assiette animée ou sur « Ouvrir mon espace ».
2. Choisissez Agent, Client, Commerçant ou Administrateur.
3. Sur la page dédiée, choisissez connexion ou inscription pour ce rôle.
4. Après connexion, vous arrivez dans le tableau de bord correspondant.
5. « Changer d’espace » vous déconnecte et ramène au choix des rôles.
Vous pouvez aussi choisir « Voir l’accueil sans compte » pour consulter la
présentation, les étapes d’utilisation et les offres déjà saisies sans commander.
Le bouton « Mon profil » permet à chaque compte connecté de modifier ses
coordonnées personnelles.

INFORMATIONS DES COMMANDES
Chaque commande conserve les coordonnées du client, du commerce et les coordonnées
administratives configurées. Le client voit les contacts du commerce et de
l’administration; le commerçant voit les coordonnées du client et de
l’administration; l’administrateur consulte l’ensemble des commandes et offres.
Configurez le nom, le téléphone, l’e-mail et le WhatsApp de l’administration dans
les paramètres de contact de son espace.

AUCUNE INFORMATION PRÉREMPLIE
Le projet démarre sans commerce, compte, panier, réservation ni statistique fictive.
Les catégories sont seulement des options de saisie. Ajoutez d'abord un commerce,
puis saisissez vous-mêmes les paniers et les réservations.

PARCOURS DE DÉMONSTRATION
1. Utilisez « S’inscrire » pour créer un compte client ou commerçant, ou « Se
   connecter » pour réutiliser un compte créé sur ce navigateur.
2. Le commerçant saisit son commerce, son contact, son adresse, son quartier et
   ses horaires, puis publie un produit vendu à l’unité ou un panier composé.
3. Le client choisit un produit ou un panier, saisit/valide ses coordonnées,
   choisit un paiement simulé et confirme la commande.
4. La confirmation affiche un QR code si la bibliothèque externe est disponible,
   ainsi qu’un code de retrait utilisable même sans QR. Le commerçant et
   l’administrateur voient immédiatement les coordonnées, l’horaire et la commande.
5. Le commerçant valide le retrait; l’heure de retrait est enregistrée. Le client
   peut ensuite noter le commerçant sur 10.
6. Configurez le numéro WhatsApp administrateur dans l’espace Administration.
   Le formulaire de contact client enregistre la demande puis ouvre WhatsApp.
7. Les clients peuvent filtrer par catégorie, quartier et type de commerce, garder
   des favoris, modifier leur profil et noter un commerce après le retrait.
8. Le commerçant voit son stock bas, sa note moyenne et valide le retrait en
   saisissant le code exact communiqué par le client.
9. L’administration peut consulter le centre de notifications et exporter les
   commandes ou les comptes au format CSV.
10. D’autres outils de démonstration : suivre un commerce, demander une alerte lors
    d’un retour en stock, appliquer un code promo, parrainer un client, programmer
    un rappel de retrait, déclarer un client absent, signaler un incident, importer
    des offres en lot par CSV et consigner les invendus donnés localement.
11. « Informations & aide » dans le menu regroupe les guides client/commerçant,
    les réponses aux questions fréquentes et les limites du mode simulation.

SIMULATION ET DONNÉES
- Wave, Orange Money, MTN Mobile Money et le paiement au retrait sont simulés.
- Aucun paiement, SMS, géolocalisation ou connexion externe n'est effectué.
- Les informations sont enregistrées dans le stockage local du navigateur utilisé.
- Les changements sont reflétés immédiatement dans les espaces de cette application.
- Une synchronisation entre onglets du même navigateur est tentée via l’événement
  de stockage local; il n’y a pas de serveur partagé ni de synchronisation appareil.
- Les données ne sont pas synchronisées entre plusieurs appareils ou navigateurs.
- La bibliothèque de QR code est chargée depuis un CDN; sans connexion Internet,
  le code de retrait reste affiché en texte.
- « Réinitialiser les données » efface les informations de démonstration enregistrées.
- Le prototype ne met pas en place une authentification de production. Les créations
  de compte servent à présenter le parcours et restent sur l'appareil.
- Les mots de passe de démonstration sont stockés localement : n’utilisez pas de
  vrai mot de passe ni d’information sensible.

FICHIERS
index.html  Page principale
styles.css  Mise en page, couleurs, responsive et animations
app.js      Navigation, formulaires et logique de simulation

Pour une commercialisation, il faudra connecter une API et une base de données,
mettre en place une authentification sécurisée et intégrer les services réels
uniquement après leur sélection et leur configuration.
