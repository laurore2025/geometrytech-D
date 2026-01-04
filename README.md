# geometrytech-D

## Modifications apportées.MR EDOUARD

### Traduction en français

Toutes les pages HTML (index.html, about.html, services.html, product.html) ont été traduites en français :

- Titres, contenu principal, méta descriptions, etc.
- Les textes visibles pour les utilisateurs sont maintenant en français.

### Bouton WhatsApp responsive

- Ajout d'un bouton WhatsApp qui apparaît au défilement vers le bas de la page.
- Le bouton est positionné en bas à droite, responsive sur tous les appareils :
  - Mobile (< 768px) : 50x50px
  - Tablette/PC (≥ 768px) : 60x60px
- Message par défaut pré-rempli : "Bonjour, je vous contacte depuis le site GeometryTech"
- Numéro WhatsApp :+509 4446-5292
  N.B +509 4446-5292 NUMERO DE MR.NICK (à remplacer par le numéro réel)

### Script ajouté

Un script JavaScript a été ajouté à chaque page pour :

- Détecter le défilement vers le bas.
- Créer dynamiquement le bouton WhatsApp.
- S'assurer que le message est inclus dans le lien WhatsApp.

Note : Remplacez le numéro de téléphone dans le script par votre numéro WhatsApp réel.

### 📱 Bouton WhatsApp Flottant – GeometryTech

📌 Description

Ce bouton WhatsApp flottant permet aux visiteurs de contacter rapidement GeometryTech via WhatsApp.
Il est discret, responsive, et intelligent :
👉 il n’apparaît pas en haut de la page,
👉 il s’affiche dès que l’utilisateur commence à scroller,
👉 et il reste visible jusqu’en bas de la page.

🎯 Comportement du bouton
🔝 En haut de la page : bouton caché
⬇️ Dès que l’utilisateur descend : bouton visible
🔚 En bas de la page : bouton reste visible
📱 Compatible mobile & desktop
🧩 Technologies utilisées

### HTML5

CSS3 (animations + responsive)
JavaScript pur (sans framework)
Compatible Bootstrap & templates anciens
❌ Aucun framework JavaScript requis
❌ Aucun fichier existant modifié

### ⚙️ Personnalisation rapide

🔢 Modifier le seuil d’apparition
Dans le script JavaScript :
if (window.scrollY > environ 50)
20 → apparition très rapide
100 → apparition plus tard

📞 Changer le numéro WhatsApp

Dans le lien :

https://wa.me/50944465292

Remplace par ton numéro au format international :

https://wa.me/INDICATIFNUMERO

💬 Modifier le message automatique
?text=Bonjour,%20je%20vous%20contacte%20depuis%20le%20site%20GeometryTech

### 🎨 Fonctionnalités visuelles

Animation pulse
Effet hover
Ombre dynamique
Bouton circulaire moderne
Position fixe (bottom-right)
