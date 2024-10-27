# Title: Configuration réseau — Aide informatique  documentation

## Configuration réseau > Aide informatique  documentation 

 [Aide informatique](https://doc.telecom-paris.fr/index.html)

  * [](https://doc.telecom-paris.fr/index.html) »
  * Configuration réseau
  * 

* * *

# Configuration réseau¶

## Site de Palaiseau¶

L’accès au réseau filaire et sans-fil de l’école est protégé par une
authentification 802.1x. Le paramétrage est décrit ci-dessous. Suivant celle-
ci vous obtiendrez des droits d’accès aux différentes ressources.

Pour les personnels et étudiants deux connexions sont possibles :

    

  * connexion filaire ou réseau WiFi Campus-Telecom :

    * accès possible aux ressources internes protégées selon vos droits

    * accès protégé à Internet permettant un usage web classique

    * conseillé pour les postes de travail de l’école

  * réseau WiFi eduroam :

    * seules les ressources internes publiques sont accessibles (ex : sites web ouvertes, messagerie)

    * accès total à Internet, cela vous permet notamment l’usage de VPN externes mais expose aussi votre périphérique

    * conseillé pour les smartphones

Les visiteurs peuvent indiférement utiliser les deux réseaux WiFi, ils
obtiendront toujours même droits correspondants au réseau eduroam.

## Eduroam¶

L’école adhère au service [eduroam](https://www.eduroam.fr/). Cela permet aux
visiteurs la connexion sur nos sites mais également la connexion au WiFi pour
les personnels et étudiants sur tous les sites couverts. Cela inclus la
plupart des établissement d’enseignement supérieur et de recherche mondiaux.

La connexion se fait également avec une authentification 802.1x avec exacement
les même paramètres que sur site.

## Paramétres de configuration¶

Les paramètres de connexion sont résumés dans le tableau ci-dessous :

Paramètre | Valeur  
---|---  
Sécurité (uniquement pour le WiFi) | WPA2 Enterprise  
Authentification (EAP phase1) | TTLS (Tunneled TLS)  
Authentification interne (EAP phase2) | PAP  
Identité externe ou identité anonyme | [anonymous@enst.fr](mailto:anonymous%40enst.fr)  
Domaine | laisser ce champ vide  
Certificat CA 1 | [`tp-2021.pem`](https://doc.telecom-paris.fr/_downloads/9c7f5589751027edfc4073b63ce7e85d/tp-2021.pem)  
Serveurs d’authentification 2 | radius.enst.fr  
Nom d’utilisateur et mot de passe | vos identifiants de connexion sur les postes de travail  
  
Note

Si votre système est administré par la DSI le paramétrage est fait
automatiquement

Procédures par systèmes :

  * [Linux](802.1x/linux.html)
  * [Mac OS](802.1x/macos.html)
  * [Windows 7](802.1x/win7.html)
  * [Windows 10](802.1x/win10.html)
  * [Android](802.1x/android.html)
  * [iPhone](802.1x/ios.html)

Notes

1

    

Le paramètre de certificat est indispensable pour sécuriser votre connexion,
sans lui un personne créant un faux point d’accès pourrait voler vos
identifiants

2

    

Le paramètre de serveur n’est pas proposé sur tous les systèmes, il renforce
la sécurité donnée par le certificat mais ne s’y susbstitue pas.

