# Change Log
Tout les changements liés à l'avatar et le stream seront documentés ici.

Aller à la [DOCUMENTATION](DOCUMENTATION.md)

✅ Terminé
🟨 En cours
⛔ Supprimé
❓ Non commencé

## [UNRELEASED - 5.4.0] - XXXX-XX-XX
### **Ajout :** 
  - **Modification du système de position :**
      - ❓ Ajout de la possibilité de changer le zoom de la version zoomé (_Molette_)
  
  - **Menus camembert :**
      - ❓ Changement couleurs selection quand modifier key est pressée
   
  - **Système de création de personnage :**
      - ❓ !Commande expliquant comment faire (!perso edit | !perso *head/body/hair/eyes* *nb/none* | !perso save)
      - ❓ Preview (avec pseudo) sur le stream du personnage en cours de création (erreur si déjà un personnage en cours de création)
      - ❓ Timeout si innactivité de 2 minutes+
      - ❓ Quand premier message du jour : son *Boop*, personnage qui apparaît avec une bulle pour dire Salut/Yo/Bonjour et le pseudo
   
### **Correction :**
  - ❓ Désactiver les alertes lorsque l'avatar est zoomé

## [UNRELEASED - 5.3.0] - XXXX-XX-XX

### Correction :
  - ✅ TTS ne lis plus les commands commençant par "!"
  - ✅ Tout les viewers sont compté dans les raids
  - ✅ Fix message auto (message au lancement du stream)
  - ✅ Fix compte de bot

### **Ajout :**
  - **Menu camembert émote (touche _Bouton E_) :**
      - ✅ Patpat classique (5 secondes) (couleur de la main lié à la couleur du pseudo)
      - ❓ Coeur interne (5 secondes)

  - **Menu camembert test alertes (touche _Shift_) :**
      - 🟨 À boire (cascade/vague icône)
      - ✅ Étirement
      - ✅ Sauvegarde
      - ✅ Follow (setup texte)
      - ✅ Raid
          - ✅ Système de preset
          - ✅ Coupe de cheveux
          - ✅ Habits (pants, body)
          - ✅ Spawn owner et viewers
          - ✅ Random preset
          - ✅ Panneau "RAID"
          - ✅ Icônes
          - ✅ Ajouter plus de coupe de cheveux (queue de cheval, long, cour 2)
  
  - **Messages automatiques :**
      - ✅ Message automatique concernant les commandes disponibles (lien github vers documentations)
     
  - **Sons :**
      - ✅ Son collisions entre objets et avatar (coeurs, touches)
      - ❓ Son Follow 
      - ❓ Son ctrl+s
      - ❓ Son Raid
      - ✅ Son Etirement
      - ✅ Son Head Pat
      
  - **Supprimer :**
      - ✅ Supprimer les commandes administrateurs

### **Modification :**
  - **Avatar :**
    - ✅ Textures avatar version pixel art

## [5.2.0] - 2025-08-14

### Correction :
  - ✅ Configuration Actions Rage
  - ✅ Configuration Paramètre microphone (Volume détection, Mute, TTS, Demute, Changer de micro)
  - ✅ Correction icône FPS pour enlever le pixel entre la lettre F et P

### Ajout :
  - **Ajout d'un fichier de configuration :**
      - ✅ Preset graphisme (low et high, msaa et aa)
      - ✅ Seuil micro
      - ✅ Numéro du micro
      - ✅ FPS maximum
      - ✅ Écran à détecter
      - ✅ Keybinds (ctrl, shift, alt, tab)
      
  - **Ajout des icones manquantes :**
      - ✅ Actions énervé
  
  - **Menu camembert test alertes (touche _Shift_) :**
      - ✅ Follow (autoalert setup)
      
  - **Modification du système de couleur :**
      - ✅ Couleur simple changé si changement couleur normal
      - ✅ Couleur gradient haut si shift
      - ✅ Couleur gradient bas si ctrl

  - **Paramètre supplémentaire :**
      - ✅ touche CTRL sur no mic -> TTS activé de mes messages dans le chat
      - ✅ Affichage de mes messages dans une bulle de texte
      - ✅ Molette pour changer de micro (D -> X)
      - ✅ Possibilité d'utiliser une couleur prédéfinie pour les actions (touche _CTRL_)
      - ✅ Activer ou désactiver ma bulle (activation automatique quand le micro est éteint ou quand le TTS est activé)
    
   - **Changement menu camerbert global :**
      - ✅ Paramètre seconde couche ajoutant taille des boutons
      - ✅ Changement de la gestion de la seconde couche
      
### Suppression :
  - ⛔ Suppression _Buggué_


## [5.0.0] - 2025-06-27
Version initial.

### Ajout :
  - **Menu camembert configuration de l'avatar (touche _Tab_) :**
      - ✅ Bouton central de retour
      - ✅ Bouton pour quitter l'application
      - ✅ Menu pour changer de couleur :
        - ✅ Couleurs prédéfinies : ✅ Rose - ✅ Bleu - ✅ Rouge
        - ✅ Couleurs personnalisées
      - ✅ Menu de position :
        - ✅ Gauche, ✅ Zoomée, ✅ Droite
      - Menu émotions/actions prédéfinies
          - ✅ Dormir : Bleu, yeux endormies, respiration lente, ventre étalé, queue ralentie
          - ✅ Normal : Rose, yeux fermés, respiration normale, queue normale
          - ✅ Flippant : Rose, yeux ouvert, respiration normale, queue normale
          - ✅ Rage : Rouge, yeux énervé, respiration rapide, queue stressé

  - **Menu camembert configuration paramètres  (touche _Alt_) :**
      - ✅ Bouton central de retour
      - ✅ Bouton pour quitter l'application
      - ✅ Menu de réglage des FPS :
          - ✅ 30 FPS
          - ✅ 60 FPS
      - ✅ Menu paramètrage de micro : **(VERSION 5.1.0)**
          - ✅ Bouton toggle de mute et de demute
      - ✅ Menu de réglage de la taille des menus (SLIDER)
      - ✅ Menu choix de l'écran où regarde l'avatar
          - ✅ Écran où est l'avatar
          - ✅ Écran à droite de l'avatar

- **Modèle 3D de l'avatar**
- **Texture de l'avatar :**
    - ✅Texture Base Color blanche mixée à une couleur donné
    -  ✅Équivalent fresnel géometrique
- **Ajout de différents yeux :**
    - ✅ Normals
    - ✅ Endormies
    - ✅ Énervés (+ "veine" rouge)
    - ✅ Ouverts
