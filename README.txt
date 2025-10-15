Bois Ivoire — Pack site moderne

Contenu:
- index.html : page d'accueil
- shop.html : boutique (catalogue + panier)
- assets/products.json : liste des produits et variantes
- assets/main.js : script principal (chargement produits, panier, checkout simple)
- README.txt : ce fichier

Instructions rapides:
1) Dézippez le dossier et ouvrez index.html dans le navigateur pour tester en local.
2) Le panier est stocké dans localStorage (cle: 'bois_cart').
3) Le module de paiement est simplifié : pour Stripe et PayPal, le site télécharge un fichier JSON de commande
   que vous pouvez utiliser côté serveur ou envoyer par email/WhatsApp au vendeur.
4) Pour activer un paiement en ligne intégré (Stripe Checkout), vous devez créer un endpoint serveur qui
   reçoit la commande et crée une session Stripe. Voir https://stripe.com/docs/payments/checkout
5) Hébergement recommandé: Netlify ou Firebase Hosting.
6) Personnalisation: modifiez assets/products.json pour changer les produits et prix. Les images utilisent Unsplash.

Prix d'exemple (FCFA) fournis — adaptez selon vos tarifs réels.
Contact: ajoutez votre adresse email dans index.html/footer et README.
