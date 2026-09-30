# Extension ChatGPT Ads pour WordPress et WooCommerce

Présentation de l’extension Allaux de suivi des conversions ChatGPT Ads pour WooCommerce : pixel OpenAI, Conversions API, attribution et consentement.

Développement et intégration par **[Emre Ucak — Allaux](https://allaux.fr/a-propos)**.

## Suivi du parcours e-commerce

Le pixel navigateur et l’envoi serveur utilisent un identifiant partagé pour dédupliquer les conversions. Le guide Allaux décrit l’association des identifiants de clic et de navigateur à la commande, le hachage des données de rapprochement et une clé API conservée côté serveur.

- Fiches produit, variations et ajouts au panier AJAX.
- Début de commande et achat.
- Créations de compte et formulaires selon le projet.
- Contrôle du consentement et mode validation avant la mise en production.

L’installation vérifie le thème, le cache, HPOS, le tunnel en blocs ou classique et les passerelles de paiement. Le périmètre de compatibilité est contrôlé sur le site concerné.

## Ressources

- [Extension ChatGPT Ads WooCommerce](https://allaux.fr/wordpress-woocommerce/extension-chatgpt-ads)
- [Guide du suivi des conversions ChatGPT Ads](https://allaux.fr/services/tracking/suivi-conversions-chatgpt-ads)
- [Module ChatGPT Ads PrestaShop](https://allaux.fr/prestashop/module-chatgpt-ads)
- [Tracking et analytics](https://allaux.fr/services/tracking)

## Recette technique

| Étape | Contrôle |
|---|---|
| Avant consentement | Aucun déclenchement publicitaire autorisé par défaut |
| Fiche et panier | Événement et données du produit cohérents |
| Achat | Statut retenu, montant et devise de la commande |
| Pixel et serveur | Identifiant partagé pour la déduplication |
| Attribution | Identifiants disponibles transmis selon le consentement |
| Validation | Formats vérifiés avant les conversions de production |

Le journal d’envoi permet de distinguer une erreur technique, une conversion acceptée et une attribution publicitaire. Les achats avec redirection de paiement demandent une recette propre à chaque passerelle.

## Présentation publique

Ce dépôt contient une présentation technique. Les sources, les accès et les données clients restent privés. Pour étudier une adaptation à votre contexte, indiquez vos outils existants, les échanges de données attendus et les contraintes d’exploitation.

## Contact

**Emre Ucak — Allaux**, développeur indépendant depuis 2019.

- [contact@allaux.fr](mailto:contact@allaux.fr)
- [WhatsApp : +33 6 21 86 33 28](https://wa.me/33621863328)
- [Décrire votre projet](https://allaux.fr/contact)
- [allaux.fr](https://allaux.fr/)
