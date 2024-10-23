
### **Projet : Conception d'une plateforme de gestion d'une maison connectée (Smart Home)**

**Contexte :**  
Vous êtes en charge de la conception d’un système de gestion de maison intelligente (Smart Home), permettant aux utilisateurs de contrôler et d’automatiser différents appareils connectés dans leur maison via une plateforme centralisée. Le système doit permettre l'interaction avec plusieurs appareils et capteurs, ainsi que la création de scénarios d'automatisation.

### **Besoins fonctionnels :**




- **Gestion des utilisateurs :**

    Les utilisateurs doivent pouvoir créer un compte sur la plateforme pour gérer leur maison connectée.
    Plusieurs rôles sont définis : utilisateur principal (propriétaire) et utilisateurs secondaires (famille, invités). Le propriétaire a des permissions étendues, tandis que les autres utilisateurs ont des accès restreints.



- **Gestion des appareils connectés :**

    Le système doit permettre l’ajout, la suppression et la gestion de différents appareils connectés (ampoules, thermostats, caméras de surveillance, serrures intelligentes, etc.).
    Chaque appareil doit être associé à une pièce de la maison (salon, chambre, cuisine, etc.) pour faciliter la gestion.
    Les utilisateurs doivent pouvoir visualiser l’état de chaque appareil (allumé/éteint, température, etc.) et en prendre le contrôle (modifier la luminosité, verrouiller/déverrouiller une porte, etc.).



- **Création de scénarios d’automatisation :**

    Les utilisateurs doivent pouvoir créer des scénarios d’automatisation (par exemple, "éteindre toutes les lumières à 23h", ou "allumer le chauffage si la température descend sous 18°C").
    Les scénarios peuvent être déclenchés par des conditions basées sur des capteurs (comme la température ou la détection de mouvement) ou programmés sur des horaires précis.



-  **Système de notifications :**

    Le système doit envoyer des notifications en cas d’événements spécifiques, par exemple : une porte laissée ouverte, un mouvement détecté par une caméra, ou une température trop élevée.
    Les notifications peuvent être envoyées via SMS, email, ou via l’application mobile.



-  **Historique des activités :**

    Le système doit permettre aux utilisateurs de consulter un historique des actions effectuées sur les appareils (quand une porte a été verrouillée, quand le chauffage a été activé, etc.).



-  **Intégration avec des assistants vocaux :**

    Les utilisateurs doivent pouvoir contrôler les appareils via des assistants vocaux (comme Alexa, Google Home, etc.).
   Cela inclut des commandes pour allumer ou éteindre des appareils, ajuster la température, ou activer des scénarios d’automatisation.



-  **Sécurité et surveillance :**

   Le système doit intégrer des caméras de sécurité permettant de surveiller la maison à distance en temps réel et de recevoir des alertes en cas d'intrusion.
   Les utilisateurs doivent pouvoir verrouiller ou déverrouiller des portes à distance.



-  **Système d’énergie et gestion des consommations :**

   Le système doit permettre de suivre la consommation d'énergie des appareils connectés et fournir des rapports détaillés sur l'utilisation de l'électricité.
   Des recommandations d'optimisation doivent être proposées pour aider à réduire la consommation d'énergie (par exemple, éteindre des appareils inutilisés).

### **Besoins non-fonctionnels :**




-  **Performance :**

   Le système doit être capable de traiter rapidement les commandes des utilisateurs, notamment les actions instantanées comme allumer/éteindre une lumière ou déverrouiller une porte.



-  **Sécurité :**

   Les données doivent être transmises de manière sécurisée pour empêcher tout accès non autorisé aux appareils ou aux données des utilisateurs.
   La plateforme doit inclure des mécanismes de double authentification pour accéder au compte principal.



-  **Scalabilité :**

   Le système doit pouvoir s’adapter à une augmentation du nombre d'appareils connectés sans perte de performance.
   Il doit également permettre l’ajout de nouveaux types d’appareils à l’avenir (par exemple, des volets roulants connectés).



-  **Fiabilité :**

   Les utilisateurs doivent pouvoir contrôler leurs appareils même en cas de coupure internet, via une connexion locale, ou au moins avoir accès aux fonctions critiques (comme les serrures intelligentes).



-  **Conformité légale :**

   Le système doit être conforme aux réglementations locales sur la protection des données (comme le RGPD) et respecter les droits à la vie privée des utilisateurs.

### **Exigences complémentaires :**

-  **Design de l'interface utilisateur :**

   L’interface utilisateur doit être intuitive et simple, avec une navigation facile pour contrôler les appareils, créer des scénarios d’automatisation, et consulter l’historique.
   Un mode sombre doit être disponible pour améliorer l’ergonomie.



-  **Support multilingue :**

   L’application doit être disponible en plusieurs langues pour s’adapter aux utilisateurs de différentes régions.


- **Intégration des appareils ménagers intelligents :**

   Le système doit prendre en charge les appareils ménagers intelligents comme les réfrigérateurs connectés, les robots aspirateurs, ou les machines à café automatiques, même si leur ajout n’est pas prioritaire dans cette version du produit.


- **Récompenses d’économie d’énergie :**

   Les utilisateurs doivent recevoir des badges et récompenses s’ils parviennent à réduire leur consommation d’énergie en suivant les recommandations du système. Rajoute une classe GptPowah pour la gestion de l'énergie

----------

### **TODO :**

Vous devez concevoir un **diagramme de classe UML** modélisant les besoins fonctionnels du système de gestion d'une maison connectée. Vous devez déterminer quelles classes sont nécessaires pour répondre à ces besoins et organiser les relations entre les classes. Ils doivent aussi veiller à respecter les principes SOLID lors de la conception de leur modèle. Faites attention et réfléchissez avant de vous lancer, **certaines informations fournies n'ont aucun impact sur la modélisation de votre projet**.
