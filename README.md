# Soundboard

**Français** · [English](README.en.md)

Soundboard est une application Windows gratuite pour jouer des sons dans Discord, tes jeux et n'importe quelle appli qui utilise un micro. Ta voix, le son de ton PC et tes sons partent ensemble dans un micro virtuel, et tu entends tout dans ton casque.

**[⬇ Télécharger la dernière version](https://github.com/khelyan2k/Soundboard-releases/releases/latest)**

---

## Sommaire

- [Ce qu'il te faut](#ce-quil-te-faut)
- [Installation](#installation)
- [Configurer Discord (ou un jeu)](#configurer-discord-ou-un-jeu)
- [Fonctionnalités](#fonctionnalités)
- [Mises à jour](#mises-à-jour)
- [Désinstallation](#désinstallation)
- [Questions fréquentes](#questions-fréquentes)
- [Vie privée](#vie-privée)

## Ce qu'il te faut

- Windows 10 (version 2004 ou plus récente) ou Windows 11, en 64 bits.
- **VB-CABLE**, le micro virtuel gratuit de VB-Audio. Pas besoin de le chercher : Soundboard propose de l'installer pour toi au premier lancement.

## Installation

1. Ouvre la page des [versions publiées](https://github.com/khelyan2k/Soundboard-releases/releases/latest) et télécharge `Soundboard_X.Y.Z_x64-setup.exe` (dans la partie **Assets**).
2. Lance le fichier. Windows peut afficher « Windows a protégé votre PC » : c'est normal pour une petite appli qui n'a pas encore de certificat payant. Clique sur **Informations complémentaires**, puis sur **Exécuter quand même**.
3. Suis l'installation. Elle ne demande pas de droits administrateur et crée un raccourci sur le Bureau et dans le menu Démarrer.
4. Au premier lancement, si VB-CABLE n'est pas encore là, un bandeau propose **Installer VB-CABLE** :
   - Soundboard télécharge le pack officiel depuis vb-audio.com et Windows vérifie sa signature ;
   - Windows demande l'autorisation administrateur (c'est un pilote audio) ;
   - dans la fenêtre de VB-Audio, clique sur **Install Driver** ;
   - redémarre le PC si VB-Audio le demande.
5. C'est prêt. Le micro virtuel apparaît dans Windows sous le nom **Soundboard MIC**.

## Configurer Discord (ou un jeu)

1. Dans Discord : **Paramètres utilisateur** → **Voix et vidéo**.
2. **Périphérique d'entrée** : choisis **Soundboard MIC (VB-Audio Virtual Cable)**.
3. Garde ton casque habituel comme **Périphérique de sortie**.
4. Dans Soundboard, ouvre **Mixage** → **Ton micro** et choisis ton vrai micro : ta voix passera par Soundboard, en même temps que les sons.

Même principe pour un jeu ou une autre appli : choisis **Soundboard MIC** comme micro.

> Si Discord coupe les sons ou les déforme, désactive sa **suppression de bruit** (Krisp) et, si besoin, son **annulation d'écho** : ils prennent la musique et les effets pour du bruit.

## Fonctionnalités

L'appli a cinq pages : **Sons**, **Mixage**, **Paramètres**, **Nouveautés** et **À propos**.

### Tes sons

- Importe tes sons avec le bouton **Importer** ou en les glissant dans la fenêtre : MP3, WAV, OGG, FLAC, M4A/AAC et AIFF, sans limite de nombre.
- Range-les dans des catégories, avec la couleur de ton choix, et retrouve-les avec la recherche.
- Chaque son a son volume (jusqu'à 200 %), en plus du volume général.
- Plusieurs sons peuvent jouer en même temps. Quand tu recliques sur un son déjà lancé, tu choisis s'il recommence, s'il se superpose ou s'il s'arrête.
- **Échap** coupe tout.

### Le lecteur

- Pause et reprise là où le son en était, et barre de position pour te déplacer dedans.
- Vitesse de ×0,5 à ×2, modifiable pendant la lecture.
- Au choix : la voix garde sa hauteur, ou devient plus aiguë en accéléré (et plus grave au ralenti), comme un disque.
- Chaque son peut avoir sa vitesse par défaut.

### Ton micro

- Ton vrai micro est mélangé aux sons : Discord reçoit ta voix et les sons en même temps, sans réglage Windows en plus.
- Volume, bouton pour couper, et raccourci pour couper ou réactiver.
- **Appuyer pour parler** avec la touche de ton choix. Les sons, eux, passent toujours.
- **Porte de bruit** réglable avec un vumètre, pour couper le clavier et le ventilateur quand tu ne parles pas.

### Le son du PC

- Envoie **tout le son de ton PC** dans le micro virtuel, comme pour un stream : musique, vidéos, jeux.
- Ou **seulement les applis que tu choisis**, parmi toutes celles qui sont ouvertes. Une sélection avancée permet aussi de prendre un programme en arrière-plan.
- **Anti-écho** à activer ou non : Discord, et les applis que tu ajoutes à la liste, sont laissés de côté pour que les gens en appel ne s'entendent pas eux-mêmes.
- Volume à part, pour que la musique ne couvre pas ta voix.

### La table de mixage

- Une tranche par source (sons, micro, son du PC) et par sortie, avec des vumètres en direct.
- Deux sorties, chacune avec son volume et son interrupteur : le **micro virtuel** (ce que Discord entend) et le **retour casque** (ce que tu entends).
- Dans le casque, tu peux entendre ta voix et le son du PC en plus des sons : exactement ce que Discord reçoit, ou tout le son du PC.
- **Limiteur** sur chaque sortie : le son ne sature pas, même en poussant le volume.
- **Profils de mix** (« Jeu », « Stream »…) à appliquer en un clic ou avec un raccourci.

### Les raccourcis

- Un raccourci par son, un pour tout arrêter, et d'autres pour le micro et les profils.
- Touches simples, combinaisons avec Ctrl, Alt ou Maj, pavé numérique, F13 à F24, boutons latéraux et molette de la souris.
- Ils marchent en plein jeu, sans bloquer la touche dans le jeu.

### Au quotidien

- Fermer la fenêtre ne quitte pas l'appli : elle reste près de l'horloge, avec un menu pour tout arrêter, couper les raccourcis ou quitter.
- Option pour lancer Soundboard au démarrage de Windows, directement réduit.
- Le micro virtuel est renommé tout seul en **Soundboard MIC**, et le périphérique inutile « CABLE In 16ch » est masqué.
- Taille de l'interface réglable (100 % au départ) ou automatique selon ton écran.
- La page **Nouveautés** liste ce qui change à chaque version.

## Mises à jour

Soundboard vérifie les mises à jour au démarrage, puis toutes les 6 heures. Quand une version sort, un bandeau te la propose : un clic, et elle s'installe toute seule. Tu peux aussi vérifier à la main dans **À propos**.

Tes sons, tes catégories et tes réglages sont conservés. Chaque mise à jour est signée : l'appli refuse tout fichier qui ne vient pas de ce dépôt.

## Désinstallation

1. **Paramètres Windows** → **Applications** → **Applications installées** → **Soundboard** → **Désinstaller**.
2. Coche **Supprimer les données de l'application** si tu veux aussi effacer tes sons et tes réglages.
3. Une fenêtre te propose de **retirer VB-CABLE** en même temps. Windows demande l'autorisation administrateur, et un redémarrage peut être nécessaire pour qu'il disparaisse complètement. Réponds **Non** si une autre appli s'en sert.

## Questions fréquentes

**Mes amis n'entendent pas les sons.**
Vérifie que Discord utilise **Soundboard MIC** comme périphérique d'entrée, et que l'interrupteur du **micro virtuel** est allumé dans **Mixage**. Désactive aussi la suppression de bruit de Discord.

**Je n'entends pas les sons dans mon casque.**
Dans **Mixage**, allume le **retour casque** et vérifie le périphérique choisi.

**L'appli dit que VB-CABLE n'est pas installé.**
Lance l'installation depuis le bandeau, clique sur **Install Driver** dans la fenêtre de VB-Audio, puis redémarre le PC si on te le demande.

**Les gens en appel s'entendent quand j'envoie le son du PC.**
Active l'**anti-écho** dans la carte **Son du PC**, ou choisis seulement les applis à envoyer.

**Un raccourci ne marche pas dans un jeu.**
Vérifie qu'il n'est pas déjà pris par le jeu ou une autre appli. Si le jeu tourne en administrateur, Windows empêche une appli normale de voir ses touches : lance alors Soundboard en administrateur, lui aussi.

**Windows a bloqué l'installateur.**
C'est le filtre SmartScreen : **Informations complémentaires** → **Exécuter quand même**.

## Vie privée

Soundboard fonctionne entièrement sur ton PC. Il ne collecte rien, n'a pas de compte et n'envoie ni tes sons ni ta voix ailleurs que dans le micro virtuel. Il se connecte à internet seulement pour vérifier les mises à jour sur ce dépôt et, si tu le demandes, pour télécharger VB-CABLE depuis vb-audio.com.

---

VB-CABLE est un logiciel de VB-Audio Software (donationware), téléchargé depuis [leur site officiel](https://vb-audio.com/Cable/). Soundboard n'est affilié ni à VB-Audio ni à Discord.
