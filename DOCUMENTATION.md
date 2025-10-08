# DOCUMENTATION
Ceci est une l'instant une preview des commandes qui sera plus tard disponible.

Toutes les commandes faisable par les **Viewers** sont faisable par les **Modérateurs**, toutes les commandes exécutables par les modérateurs sont exécutable par les **Administrateurs**

Les commandes dans la documentation se présentent tel que :

**!nom commande [option] [paramètre]** : _Réponse_

## Pour les Viewers

| État | Commands       | Alias | Descriptions     |
|:----:|----------------|-------|------------------|
| 🟨 | **!help**          |*none* | _Voici la documentation de l'avatar : **[Documentation](https://github.com/Torvosaure/avatarSlimeChat/blob/main/DOCUMENTATION.md)**_   |
| ✅ | **!ping --love *nb*** | !amour / !love | _M'envoyer des coeurs_ |
| ✅ | **!ping --save** | !sauvegarde / !save | _Me rappel de sauvegarder_ |
| ❓ | **!ping --drink** | !bois / !drink | _Fait apparaitre une bouteille d'eau tombante et effecture un effet sonore_ |
| ❓ | **!ping --stretch** | !etirement / !stretching | _Me rappel de m'étirer_ |
| ✅ | **!change --avatar angry** | !enerver / !angry | _Applique l'avatar énervé pendant 5 minutes (si vous considéré que je suis actuellement énervé)_ |
| ❓ | **!emote --*emote*** | !patpat | _Les émotes sont : patpat (5 secondes)_ |

## Pour les Modérateurs

| État | Commands       | Alias | Descriptions     |
|:----:|----------------|-------|------------------|
| ❓ | **!echo --tts *message***          | !tts *message* |  _Permet de faire lire un message au Text To Speech_  |

## Pour les Administrateurs

| État | Commands       | Alias | Descriptions     |
|:----:|----------------|-------|------------------|
| ✅ | **!change --avatar sleeping** | !endormie / !sleeping | _Applique l'avatar endormie_ |
| ❓ | **!change --color *color*** | !setcolor *color* | _Couleurs acceptées : Bleu, Rose, Rouge_ |
| ❓ | **!change --position *position*** | !setpos *position* | _Positions disponibles : Gauche, Droite, Zoomé_ |
| ❓ | **!shutdown now** | !quit | _Quitte l'application avatar_ |
| ❓ | **!setmic --mute *on/off*** | !mute (toggle) | _Mute ou demute la detection du microphone_ |
| ❓ | **!setmic --volume *float*** | !volmic *float* | _Définie la sensibilité de la détection du microphone (0.1)_ |

---

# Raccourcis clavier

## Globals :
  - ✅ **Clic droit** : Retour en arrière

## Menu avatar :
  - ✅ **TAB** : Ouvre le menu de configuration de l'avatar
  - ✅ **CTRL + Clic gauche** _sur preset des yeux_ : Utilise le preset sans changer la couleur

## Menu Paramètres :
  - ✅ **SHIFT** : Ouvre le menu de configuration générale
  - ✅ **Micro** :
      - ✅ **Molette** _sur icône micro Default_ : Change le micro sélectionné
      - ✅ **CTRL + Clic gauche** _sur l'icône de mute_ : Active et désactive le TTS (active visibilité de mes messages)
      - ✅ **Clic gauche** _sur l'icône de mute_ : Active et désactive le Microphone
      - ✅ **Molette** _sur l'icône de mute_ : Diminue et augmente la sensibilité de détection du microphone
  - 🟨 **Icône zoom** :
      - 🟨 **Molette** : Change zoom (non sauvegardé)

## Menu Alertes :
  - ✅ **ALT** : Ouvre le menu de test d'alerte
  - 🟨 **Raid** :
      - 🟨 **Molette** : Choisir preset/random
