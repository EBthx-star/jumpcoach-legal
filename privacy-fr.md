# Politique de confidentialité — JumpCoach

**Dernière mise à jour :** 8 novembre 2026
**Éditeur :** Ixsence — Emmanuel Barthoux
**Contact :** emmanuel.barthoux@ixsence.com

---

## En une phrase

JumpCoach **ne collecte, ne transmet et ne vend aucune donnée personnelle**. Toutes vos reconnaissances, profils chevaux et paramètres restent **sur votre iPhone**.

---

## Ce que JumpCoach **ne fait pas**

- ❌ Aucun compte utilisateur, aucune inscription
- ❌ Aucun serveur, aucun backend JumpCoach
- ❌ Aucun service d'analyse (Google Analytics, Firebase, Mixpanel, etc.)
- ❌ Aucun identifiant publicitaire (IDFA), aucune publicité
- ❌ Aucun partage avec des tiers
- ❌ Aucun suivi entre apps (App Tracking Transparency : refusé par défaut)

---

## Les données que JumpCoach utilise, **localement, sur votre appareil**

### Position GPS
- **Pourquoi :** tracer votre reconnaissance et géolocaliser les obstacles.
- **Où :** mémoire de l'app uniquement, dans le conteneur de JumpCoach.
- **Partagée avec Apple ?** Non.

### Micro + reconnaissance vocale
- **Pourquoi :** identifier les commandes « Vertical », « Oxer », « Palanque » que vous dictez pour poser un obstacle sans toucher l'iPhone.
- **Où :** le traitement est fait par la **reconnaissance vocale d'Apple**. Selon les réglages de votre iPhone (Réglages → Confidentialité & Sécurité → Dictée / Siri), l'audio peut être transmis aux serveurs d'Apple pour transcription. **JumpCoach ne reçoit que le texte final** et ne conserve pas l'audio.
- **Documentation Apple :** [https://support.apple.com/HT210657](https://support.apple.com/HT210657)

### Mouvement (accéléromètre)
- **Pourquoi :** mesurer la longueur de foulée de votre cheval et détecter les sauts en mode tour à cheval.
- **Où :** traitement local, pas de transmission.

### Reconnaissances et profils chevaux
- **Où :** stockés dans `UserDefaults` (préférences iOS standard), dans le conteneur privé de JumpCoach.
- **Sauvegardes :** à votre demande, JumpCoach génère un fichier `.json` que vous pouvez partager vers **iCloud Drive** via la feuille de partage iOS. C'est vous qui décidez où envoyer ce fichier ; Apple applique sa propre politique de confidentialité iCloud à son stockage.

---

## Communication Apple Watch ↔ iPhone

Si vous utilisez l'app compagnon Apple Watch, les obstacles posés depuis le poignet sont transmis à votre iPhone via **WatchConnectivity** (canal privé Apple entre vos 2 appareils appairés). Aucune donnée ne quitte vos appareils.

---

## Permissions iOS demandées

| Permission | Pourquoi |
|------------|----------|
| **Localisation en cours d'utilisation** | Enregistrer le tracé GPS pendant la reconnaissance à pied |
| **Localisation en arrière-plan** | Continuer l'enregistrement quand l'iPhone est dans la poche pendant le tour à cheval |
| **Micro** | Dicter les commandes vocales de pose d'obstacles |
| **Reconnaissance vocale** | Traduire la dictée en commandes |
| **Mouvement (accéléromètre)** | Mesurer la foulée et détecter les sauts |

Vous pouvez révoquer chaque permission à tout moment dans **Réglages → JumpCoach**.

---

## Vos droits (RGPD)

Puisque **aucune donnée ne quitte votre iPhone**, il n'y a rien à exporter, rectifier ou supprimer côté éditeur. Les données vous appartiennent et restent chez vous.

Pour supprimer toutes vos données JumpCoach : **supprimez l'app**. Tout est effacé.

Pour toute question : **emmanuel.barthoux@ixsence.com**.

---

## Changements à cette politique

Si cette politique change, la nouvelle version remplacera celle-ci à la même URL, avec la date mise à jour en haut de page.
