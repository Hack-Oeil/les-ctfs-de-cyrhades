Les CTFs de Cyrhades
====================


**Accès au discord** : [https://discord.gg/FkFh55qcBz](https://discord.gg/FkFh55qcBz)

🎉 🥳 **Nouvelle version en Java.** 🥳 🎉

Vidéo de Présentation
----------------------
[Regardez la vidéo](https://www.youtube.com/watch?v=_uJcXd6Kkhc)



<img src="resources/interface.png">
Des challenges seront ajoutés réguliérement (environ 1 par semaine)

Bon challenges à tous !

----------------------

Concernant cette nouvelle version il n'y a aucun CTF d'intégrer de base, vous téléchargez via l'interface uniquement ceux que vous souhaitez faire.

Installation
------------
> git clone https://github.com/Hack-Oeil/les-ctfs-de-cyrhades

Vous pouvez lancer l'application en double cliquant sur **les-ctfs-de-cyrhades.jar** ou avec la commande : 
> java -jar les-ctfs-de-cyrhades.jar



pour démarrer SOUS MAC 
------------
pour mettre à jour :
> java -jar app.jar

puis pour démarrer l'appli :
> java -jar app.jar


Dependances
-----------
🐋 Docker est indispensable pour les challenges dockerisés, comme c'est le cas pour les catégories WEB et Programmation.
Cependant il n'est pas obligatoire si vous utilisez l'application pour les challenges  de type cryptanalyse, stéganographie, forensic, OSINT. 


🏴 Les CTFs  :
----------------
- **Cryptanalyse**
    - **CRYPTANALYSE_SUR_MD5** : Déchiffrer déchiffrer du MD5
    - **CRYPTANALYSE_CODE_DE_CESAR_1** : Ave, César !
    - **CRYPTANALYSE_BASE64_DIVISE_PAR_2** : Vous connaissez le Base 64, c'est un bon début alors ...
    - **CRYPTANALYSE_ASCIIPARAIT** : L'hexa c'est facile Ascii parait
    - **CRYPTANALYSE_VIGENERE** : Petite lettre à un ami
    - **MESSAGE_AU_ROI** : Message au roi Polybe
    - **WAR_MESSAGE** : Message seconde guerre mondiale

- **Forensic**
    - **DOUBTFUL_USB** : Clé USB douteuse

- **OSINT**
    - **OSINT_A_LA_CAMPAGNE** : Retrouvez l'endroit où a été prise la photo"
    - **OSINT_CHIEN_PERDU** : Chien perdu
    - **OSINT_VOYAGE_NOOBOSAURUS_R3X** : Le voyage de Noobosaurus R3x
    - **RDV-W3W** : Agent X Rendez-vous demain 21h

- **Programmation**
    - **LA_CARTE_MANQUANTE** : La carte manquante
    - **CLAIR_DE_LUNE** : L'algorithme de Luhn, également connu sous le nom de "modulus 10"
    - **IMAGE_PAS_TRES_JOLIE** : Une image pas très jolie
    - **MELODIOUS_SOUNDS_OF_THE_SHADOW** : Les sons mélodieux de l'ombre
    
- **Stéganographie**
    - **STEGANO_EXERCICE_1** : Une image mais pas que
    - **STEGANO_EXERCICE_2** : Sage comme une imageS
    - **STEGANO_EXERCICE_3** : A la recherche des pixels presque invisibles
    - **IMAGE_PAS_TRES_JOLIE** : Une image pas très jolie
    - **MELODIOUS_SOUNDS_OF_THE_SHADOW** : Les sons mélodieux de l'ombre
    - **STEG_IMAGE_SECRET_MESSAGE** : Message secret dans une image
    - **STEG_AUDIO_SECRET_MESSAGE** : Message secret dans un fichier audio
    - **OFFICE_MATRIOCHKAS** : DOCx et XLSx poupées russes
    - **HARMONY_AND_SILENCE** : Les sons mélodieux de l'ombre 

- **Web client**
    - **XSS_REFLECTED** : Chercher la faille XSS Reflected
    - **XSS_DOM_TRADINGVIEW** : XSS Dom, donnez votre langue au chat
    - **WEB_CLIENT_DISABLED_BUTTON_AND_CONTROL** : Le bouton est désactivé mais même en le réactivant on ne peut pas jouer !
    - **XSS_DOM_TRADINGVIEW_2** : XSS Dom, cette fois c'est pas les cookies !
    - **CRLF_XSS_STORED_SESSION** : Un pirate a voulu nous tendre un piège, retournez la situation.
    - **FORMUL_NO2** : Formulaire en chamboule tout
    - **JS_PASSWORD_CLIENT** : Password coté client = inutile

- **Web serveur**
    - **PHP_LFI_RFI_WRAPPER_FTP** : Injection de fichier et gestionnaire de Flux FTP
    - **PHP_WEAK_SESSION** : Session Faible
    - **NODE_DIRECTORY_TRAVERSAL** : Directory Traversal (Navigation dans les répertoires)
    - **NODE_PUG_DOCTYPE_ZERO_DAY** : Faille Doctype PUG Zéro Day
    - **PHP_IDOR_AND_MAGIC_HASH** :  Insecure Direct Object Reference et Magic Hash
    - **CTF_AFFAIRE_CLASSEE** :  Le timestamp, c'est pas pour toute la vie en 32bits
    - **UNSERIALIZE_CONVERSATION** : Ne vous laissez pas distraire par la discussion
    - **PHP_CTF_ASSERT_LFI** : Assert à pas grand chose cette sécurité
    - **PHP_COOKIE_SERIALIZE_LOOSE_COMPARAISON** : Devenez admin en émiettant le cookie
    - **LOCAL_FILE_INCLUSION_BUILD_CSS** : Un builder CSS maison
    - **LOCAL_FILE_INCLUSION_DOWNLOAD** : Téléchargement de fichier sans contrôle
    - **INJECTION_SQL_UNION_SELECT** : Dans cet exercice il est possible de chercher des vêtements, mais pas que.
    - **INJECTION_SQL_ROUTED** : En fonction de la catégorie choisie, les articles associés sortiront.
    - **INJECTION_SQL_AUTHENTIFICATION_1** : L'email puis le password (hashé) dans une requête SQL non sécurisée
    - **INJECTION_SQL_AUTHENTIFICATION_2** : Le password (hashé) puis l'email dans une requête SQL non sécurisée
    - **INJECTION_SQL_ROUTED_2** : Le développeur a changer sa façon de s'y prendre, il utilise maintenant un id et il utilise la fonction addslashes, pour éviter les guillemets, d'après lui cela empéchera l'injection SQL.
    - **PHP_LFI_RFI_WRAPPER_FTP_ZIP** : LFI/RFI Wrapper FTP + ZIP
    - **IDOR_CODE_SOURCE_1** : IDOR pour trouver le mot de passe de l'administrateur et se connecter
    - **EJS_INJECTION_CVE_2022** : EJS injection - CVE-2022-29078
    - **SQL_LIKE_A_BOSS** : Authentification SQL - LIKE a boss
    - **COMMAND_INJECTION_NSLOOKUP** : DNS MX - injection de commande
    - **WAV_CONVERTER_ONLINE** : Conversion de fichier wav en mp3
    - **EVAL_ECHEC_ET_MATH** : eval(ECHEC ET MATH)
    - **IDOR_CODE_SOURCE_2** : IDOR, Code Source et hash
    - **SQL_INJECTION_BLIND_1** : Pas vu pas pris
    
- **Divers**
    - **CTF_PRESENTIEL_1** : CTF à faire en présentiel, lock picking + dumpster diving
    - **CTF_SSRF_PHILIPS_HUE** : Allumer une ou plusieurs lumière(s) chez le formateur.
    - **CTF_SSRF_WITHOUT_PHILIPS_HUE** : Allumer les lumière(s) fictive(s) visible(s) via une caméra virtuelle OBS.

- **Réaliste**
    - **VOL_TABLETTE_EGYPTIENNE** : La momie