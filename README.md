# TP_Synth-se_Info_CHARUEL

L'objectif principal du travail pratique était de développer un client TFTP pour le transfert de fichiers en conformité avec les normes du protocole. Les programmes "gettftp" et "puttftp" ont été créés pour accepter des arguments en ligne de commande, simplifiant ainsi l'obtention des informations nécessaires sur le serveur et le fichier. Pour assurer une résolution d'adresse fiable, la fonction "getaddrinfo" a été utilisée pour résoudre l'adresse du serveur en fonction des informations passées en ligne de commande. Une fois ces informations obtenues, un socket a été réservé pour établir la connexion nécessaire au transfert de données.

En ce qui concerne le transfert de fichiers, plusieurs fonctionnalités conformes aux normes du protocole TFTP ont été implémentées. Une fonction a été développée pour construire correctement une requête de lecture (RRQ) conformément à la RFC1350.
