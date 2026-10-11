CLUB DE MOTONEIGE SAINT-CÔME — Boutique (même format que Club Mauricie / FCMQ, paiement Square)

1) Netlify > Environment variables :
   SQUARE_ACCESS_TOKEN = (même token que les autres boutiques)
   SQUARE_LOCATION_ID  = LKBN9910T1M36

2) EmailJS (merci.html, lignes 34-35) : même clé publique que les autres boutiques.
   Remplacer service_XXXXXXX (service Gmail de la boutique)
   et template_XXXXXXX (dupliquer le template Club Mauricie, mêmes variables,
   changer les destinataires).
   Tant que ces deux valeurs ne sont pas remplies, aucun courriel de commande n'est envoyé.

3) Prix/produits : 3 endroits identiques
   index.html, merci.html, netlify/functions/create-checkout-session.js
